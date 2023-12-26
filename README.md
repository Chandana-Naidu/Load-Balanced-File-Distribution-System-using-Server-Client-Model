# Load-Balanced-File-Distribution-System-using-Server-Client-Model

Description:

Our innovative Server-Client model in Linux, designed with C programming, introduces a sophisticated load-balancing mechanism for efficient file distribution. The architecture consists of a Server, a Mirror, and multiple Clients, creating a seamless and responsive network for file requests.

**Server:**
The Server acts as the central hub, managing communication between Clients and the Mirror. It intelligently distributes client requests based on the current load. When the load is high, the Server offloads some requests to the Mirror, ensuring optimal resource utilization. The Server orchestrates the flow of data, maintaining a robust connection with both the Mirror and Clients.

**Mirror:**
Functioning as a mirror image of the Server, the Mirror plays a crucial role in load balancing. It shares the client-handling responsibilities with the Server, providing redundancy and enhancing system reliability. The Mirror receives redirected requests from the Server and responds with the requested files, lightening the load on the Server during peak times. This collaborative approach ensures scalability and minimizes response times.

**Client:**
Clients initiate file requests and establish direct connections with the Server. The communication is transparent, with Clients unaware of the dynamic load balancing happening behind the scenes. The system prioritizes responsiveness, ensuring Clients receive their requested files promptly, whether directly from the Server or via the Mirror.

**Load Balancing:**
The load balancing algorithm monitors the system's current load and intelligently redistributes incoming client requests between the Server and the Mirror. This dynamic approach optimizes resource utilization, prevents bottlenecks, and enhances the overall system performance.

**Benefits:**
- Efficient resource utilization through dynamic load balancing.
- Improved system responsiveness during high-traffic periods.
- Redundancy and fault tolerance with the Mirror sharing client-handling duties.
- Seamless file distribution for Clients, irrespective of the backend load management.

Our Server-Client model with load balancing redefines file distribution, ensuring a scalable and responsive system in the Linux environment. This architecture addresses the challenges of handling varying client loads, providing an adaptive and reliable solution for file requests.

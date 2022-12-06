# Best Practices for Building Solutions on AWS

### Evaluate tradeoffs so that you can select optimal approach.

-  You might trade consistency, durability, and space for time and latency to 
    deliver higher performance. 

- You might prioritize speed to market over cost.

---

### Best Practices

1. Enable Scalability
    - Use services like Amazon EC2 Auto Scaling to scale out the servers.

2. Automate the Environment
    - Amazon EC2 Auto Scalaing can scale the servers based on certain metrics.

3. Treat Resources as disposable
    - Automate deployment of new resources with identical configurations.
    - Terminate resources when they are not in use
    - Switch to new IP address automatically.

4. Use loosely coupled components
    - Decouple the architecture with services like Elastic Load Balancing, message queues.

5. Design services not servers.
    - When appropriate, consider using containers and serverless solutions.
    - Use message queues to handle communication between web servers.

6. Choose the right database solution
    - Consider read-write needs, latency, storage requirements, nature of queries, concurrent connections and many more before choosing any database.

7. Avoid single point of failure
    - Assue everything fails and then design backward
    - Use redundancy to prevent SPOF. Example: database replication

8. Optimize for cost
    - Take advantages of flexibility of aws to increase cost efficiency.

9. Use caching
    - Use services like Amazon CloudFront

10. Secure the entire infrastructure
    - Build security at every layers of the infrastructure.
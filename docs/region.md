# AWS Region

- An AWS Region is a geographical area.

- Each AWS Region consists of two or more availability zone.

- When we store data in a specific Region, it is not replicated outside that Region. It is our responsibility to replicate data across Regions, if our business needs require it. 

- Communication between Region uses AWS backbone network infrastructure.

- To achieve fault tolerance and stability, regions are isolated from one another.

<small>Fault tolerance refers to the ability of a system to continue operating without interruption when one or more of its components fail.</small>

### Things to take care while selecting any region

1. Data governance and legal requirements
2. Proximity to customers (latency)
3. Services available within the region
4. Costs (vary by region)
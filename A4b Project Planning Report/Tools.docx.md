Related Works Paper:

[https://medium.com/agoda-engineering/how-we-solve-load-balancing-challenges-in-apache-kafka-8cd88fdad02b](https://medium.com/agoda-engineering/how-we-solve-load-balancing-challenges-in-apache-kafka-8cd88fdad02b)

Blog post on load balancing in Kafka applications highlights their approach using lag-aware producers and consumers. While their solution effectively addresses load imbalances, our project offers distinct advantages.

Our project focuses on a cloud-based telemetry system for SDN networks, leveraging the scalability and cost-effectiveness of cloud infrastructure. We aim to integrate with network management tools, utilize advanced data analysis techniques, and accommodate diverse SDN environments. Unlike Agoda's solution, our project prioritizes scalability at the network level, cost-effectiveness, and open-source integration.

[https://und.primo.exlibrisgroup.com/permalink/01ODIN\_UND/1sb5k4m/cdi\_unpaywall\_primary\_10\_1007\_s11227\_021\_03955\_6](https://und.primo.exlibrisgroup.com/permalink/01ODIN_UND/1sb5k4m/cdi_unpaywall_primary_10_1007_s11227_021_03955_6)

Tools:

[https://www.geeksforgeeks.org/go-programming-language-introduction/\#](https://www.geeksforgeeks.org/go-programming-language-introduction/)

[https://openobserve.ai/blog/analyzing-network-traffic-using-netflow](https://openobserve.ai/blog/analyzing-network-traffic-using-netflow)

[https://endjin.com/blog/2022/01/introduction-to-containers-and-docker](https://endjin.com/blog/2022/01/introduction-to-containers-and-docker)

[https://www.geeksforgeeks.org/introduction-to-docker/](https://www.geeksforgeeks.org/introduction-to-docker/)

[https://hackmd.io/@rse2021/lab1](https://hackmd.io/@rse2021/lab1)

[https://docs.openvswitch.org/en/latest/](https://docs.openvswitch.org/en/latest/)

Software-Defined Networking (SDN) has emerged as a transformative paradigm in network management, decoupling the control plane from the data plane. This separation enables centralized management and control of network resources, facilitating greater flexibility, scalability, and programmability. To effectively monitor and manage SDN networks, a robust telemetry system is essential. Telemetry systems collect and analyze network data, providing valuable insights into network performance, resource utilization, and security.

OpenFlow

A standardized protocol for controlling network devices, enabling programmatic configuration and management.

Provides a foundation for SDN implementations and facilitates the collection of telemetry data.

Mininet

A virtual network emulator that allows for the creation and testing of various network topologies and configurations.

Offers a flexible environment for developing and evaluating SDN applications and telemetry systems.

Go (Golang)

A modern, high-performance programming language designed for building scalable and efficient applications.

Offers strong concurrency features, garbage collection, and a simple syntax, making it suitable for network programming and telemetry systems.

Kafka

A distributed streaming platform designed for handling real-time data ingestion and processing.

Offers high throughput, low latency, and fault tolerance, making it suitable for handling large volumes of telemetry data.

Open vSwitch (OVS)

A virtual switch that can be deployed on a variety of platforms, including physical servers, virtual machines, and containers.

Provides a flexible and scalable solution for connecting virtual machines and containers to physical networks.

Offers support for OpenFlow, making it a key component of many SDN environments.

 Docker and Containers

Docker provides a platform for packaging applications into containers, which can be easily deployed, managed, and scaled across different environments.

Containers offer improved portability, isolation, and resource efficiency compared to traditional virtual machines.

Our telemetry system can be packaged as a containerized application, making it easier to deploy and manage in cloud environments.
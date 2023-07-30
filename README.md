# littleSwarm
For a project with 10 web services, I decided to run them all on Docker and use Swarm as an orchestrator. The owner of these web services obtained an account from a public cloud provider in Iran.
In the first step, I created a private network on the cloud provider's platform and connected all of the services to this network.
In the second step, I created a base image and a swarm cluster with three nodes. All three nodes were swarm managers and were capable of running containers. In my opinion, the most interesting thing about this project was the load balancer. I deployed it using the instructions in [this link]: (https://www.haproxy.com/blog/haproxy-on-docker-swarm-load-balancing-and-dns-service-discovery). I also used built-in socket service discovery and overlay network for this project.
![all-replicas-per-node@0 75x](https://github.com/rezadarzi/littleSwarm/assets/31057674/ca9be8ba-f54f-462b-abb3-8c8c06d82fa6)

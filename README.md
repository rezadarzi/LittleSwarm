# littleSwarm
For a project with 10 web services I decide to run all of then on docker and use swarm as orhesraitor. The owner of these web services get an account from a public cloud provider in Iran.
At first step I create a private network on it and connect all of serveres to this network. 
At second step I create base image and then create a swarm cluster with three node. All three node are swarm manager and all of them cpable run container. In my oponin The most intresting thing in this project is load balancer.

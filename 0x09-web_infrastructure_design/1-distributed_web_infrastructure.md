-For every additional element, why you are adding it? We use a redundant resource and 
we put a load balancer infront of those resources and we will access both resources at
the same time and the two identical resources will syncronize each other, so which ever the resource we access we will get the same data.

-What distribution algorithm your load balancer is configured? Round Robin: This algorithm is the most commonly implemented. It works by using each server behind the load balancer in turns, according to their weights. It’s also probably the smoothest and most fair algorithm as the servers’ processing time stays equally distributed. As a dynamic algorithm, Round Robin allows server weights to be adjusted on the go.

-Is your load-balancer enabling an Active-Active or Active-Passive setup, explain the difference between both:- I choose active-active load balancer, active-active load balancing needs atleast two nodes, both actively running the same kind of servicesimultaniously, loadbalancing distribute workloads across all nodesin order to prevent any single node from getting overloaded. An active-passive cluster also consists of at least two nodes, but as the name implies if one of the node is active the other on is going to be passive or on standby.The passive (failover) server serves as a backup that's ready to take over as soon as the active (primary) server gets disconnected or is unable to serve.

-How a database Primary-Replica (Master-Slave) cluster works:-How a database Primary-Replica (Master-Slave) cluster works.

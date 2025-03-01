
## Networking in distributed systems
- API's rely on network communication for functionality 
- Understanding networks can help diagnose and optimise system behaviour such as :
	- Performance and reliability
	- Communication and security
	- Consistency and middleware	 
###  What are distributed systems ?
- multiple independent machines together
- hides the complexity of networking (by appearing as a single entity)
- communicates over a network (such as LAN, WAN or the internet)
- components located at networked computers communicate and coordinate their actions solely via message passing
###  Advantages of distributed systems 
- Scalability : possible to add and remove nodes
- Share resources : share hardware stuff (printers and all that), software stuff (files, databases and all that), and computational power / storage
- Fault tolerance : components can fail independently, leaving others running 
- Concurrency : Concurrent computations and coordination of components
- Availability : high system availability despite failures
###  Challenges with distributed systems 
- Complexity : difficult to design, implement and debug
- Latency : communication over a network
- Consistency : Achieving consistency across nodes can be challenging (CAP theorem)
- Security : more nodes means more points of attack
### Stuff that will be covered (can use as checklist for exams): 
- #### [[Week 1]] :
	-  Foundational Communication in Networking
		- will be looking at mechanisms that ensure reliable, error-resilient communication, efficient resource sharing, and seamless connectivity across diverse network environments
			- Media and transmission methods
			- Link layer functions
			- MAC protocols
			- Error handling
			- Layer models
- #### Week 2 :
	-  tbd will do when i make notes for week 2

### Application Domains
- Finance 
- eCommerce
- The information society
- Healthcare
- Education
- Science
- Transport & Logistics
- Environment 
- Online games
### Trends in Distributed Systems
- #### Pervasive/ IoT networking 
	- many computer networks of different types
	- set of services is open-ended
- #### Mobile and ubiquitous computing 
	- Portable devices
	- Access while on the move
	- Context-aware computing (use of nearby resources through service discovery)
- #### Distributed multimedia systems
	- Technologies for locating/storing/transmitting multimedia
	- Services on-demand
- #### Cloud computing
	- cluster computer provides single, integrated storage and compute power
	- Removes reliance on localised network resource management
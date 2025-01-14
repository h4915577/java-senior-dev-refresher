Microservices vs Monoliths

When to go for microservices and when to go for monolith. Wanted some practical examples.

Having a shared DB between microservices, is it good or workable?

How to scale a DB?

How do you scale a microservice?

What's saga pattern? why you are using it? Give an example (e-commerce, or any example)

Explain API Gateway

Hystrix - I mentioned that I am using Hystrix for fallBackMethods and we have to add the dependency  Spring-cloud-starter-hystrix and we have to do some stuffs in yml file
	    Spring:
		  cloud:
		     gateway: 
			    filters:
				   - name : CircuitBreaker
				     args : name : Order_Service (suppose)
					 fallbackUri: forward: /orderFallBack
		
		Suppose any service is down so we have to send fall-back response to client 

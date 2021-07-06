# Testbase

#Instruction

#Technical Requirement

Backend

MoneyPal is a fictitous marketplace system where user have offers and request for services. Users 
have a virtual wallet where they can credit their wallet from within the system. The goal of this
mini project is to build a backend services using the microservice architecture to facilitate transfer
of money from a wallet to another wallet. Note that, the said system has a user service, payment service and
billing service respectively. The objective is:
	
	A. Create an authentication mechanism for registering and authenticating user. Please note, We do
		not require that the user is verified before they can use the system
	B. When an authenticated user credits a service provider we want the user (from his wallet) We want the payment
		Gateway (Paypal) to process the payment and then route it back to a messaging broker (RabbitMq or Kafka) to the billing service
	C. Upon notification from the broker, we want the billing service to deduct from the client wallet and credit
		the service provider's wallet the amount paid by the client

1. NB You can use any backend technologies to build this Notably, Java, Springboot, NodeJs, Python
2. You are also expected to containerize the app using docker
3. You are also expected to write unit tests and integratiion test for your code
4. setup a CI/CD pipeline and orchestration for the container

Frontend

1. You are required to build a mobile friendly user interface that assist the user to register and logon to the 
system
2. We also need an interface that allows the client to make payment
3. We also need an interface that shows the report on the billings and payment

NB You can use React or Angular or Vue. The frontend component must

1. Have unit test and e2e test in place
2. It must be containerize
3. You can also use kubernetes for orchestration
4. Set up CI/CD pipelines for that
5

NB Application must be deployed to AWS.

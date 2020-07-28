# Pact-JVM-Example
Basic example of Consumer driven contract testing using Pact JVM

Commands used to execute upload of pact-file and doing pact verification on Provider side: 

mvn pact:publish [run this from the provider project]

mvn pact:verify  [run this from the consumer project]


# How to start the pact broker ?

Use the command `docker-compose up -d` from the `~/pact-contract-testing/dockerpactbroker/` folder.
It can be accesses `http://hostname/`


## Create a headless service for Cassandra 

	kubectl apply -f cassandra-service.yaml

## Deploy Cassandra statefulSet
	
	kubectl apply -f cassandra-statefulset.yaml

## Note: 
Here we are simply using the non-persistent volume. You shall use persistent volume to use cassandra 


Reference: 

https://kubernetes.io/docs/tutorials/stateful-application/cassandra/


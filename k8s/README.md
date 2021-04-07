UDAGRAM Microservices
===================

Had to break the original udagram project into three "microservices". One handling users, other handling feed, and another for frontend.
Then, we made the docker containers configuration for the two backend microservices, one for the frontend, and one for the reverse proxy.
Then, we set up the CI on travis.
Then, we made the k8s deployment configuration into aws eks service. 
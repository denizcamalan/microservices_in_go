# microservices_in_go


service A app (publisher)  --->  send message      ----
                                                      | 
                                                      | (mqtt)
                                                      | 
service B app (subscriber) --->  resieved message  <---


# Getting Started

1. git clone https://github.com/denizcamalan/microservices_in_go.git

2. cd microservices_in_go

3. Run application
```
docker-compese up -d
```

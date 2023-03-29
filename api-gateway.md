### What is API-Gateway.
### source: https://www.youtube.com/watch?v=UVA5Dw12aVI&list=PL5KTLzN85O4ISx9guOjbynlhCxB87xmUq
```
Amazon API Gateway deployment
-----------------------------

Edge-optimized-endpoint 
Amazon-cloud-front > API-Gateway  :- Reducned latency for request
Regional endpoint > API Gateway :-  request from same region
Private endpoint > API Gateway :- same vpc


API Gatway - Caching 
you can add caching to API calls by providing an Amazon API
Gateway cache and specifying its size in GBs


users > MYAPI > API_cache > Production 


#API Gateway Throttling
By default API Gateway limits the steady state request rate to 10,000 request per second
```

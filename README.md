# JMeter Load & API Tests  

Performance and API testing on public endpoints.  

### Tools  
- JMeter 5.6+ (GUI + CLI)  
- Tested on JSONPlaceholder (fake API – no blocks)  

### Tests Included  
- DELETE /posts/1 – 5 concurrent users, ramp-up 10s  
  - Method: DELETE  
  - Server: jsonplaceholder.typicode.com  
  - Path: /posts/1  
  - Results: 100% success, avg 50ms response (screenshot below)  

- GET /posts – 10 users, ramp-up 20s  
  - Full list fetch, no errors

- POST /posts - 10 users - ramp-up 10s
   - creates fake entry, 100% success 

### Results  
(See .png for results)  
(Shows 200 OKs, low latency – full run in View Results Tree) 

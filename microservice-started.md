Microservice communication only via the API

The distribution of stateful logic across independent systems is a hard problem

Cascading Failure

A service fails because one of its dependencies fails

Robust Automation

Tests Deployment Monitoring Scaling

## Synchronous Communication Architecture

![image](https://user-images.githubusercontent.com/40006814/162064876-a15889c1-4ae8-49e2-957a-a0a25cda837a.png)

![image](https://user-images.githubusercontent.com/40006814/162064946-8fe8bb1e-8288-4704-90b5-4c907d1eae3c.png)

![image](https://user-images.githubusercontent.com/40006814/162065137-4ccaf91c-09a3-44d2-b1fd-a84a777bc5d5.png)

RPCs are useful: 1.Simplicity 2. Easy to reason about 3. Easy for automation test

RPCs as Microservice API = Programming Language + Web framework + HTTP endpoints

service discovery

![image](https://user-images.githubusercontent.com/40006814/162066045-6d74a6d9-e6e8-4561-a490-bafc31a50415.png)

![image](https://user-images.githubusercontent.com/40006814/162067662-b8495d0b-b97d-4b71-89f8-0c5c5c385a08.png)

![image](https://user-images.githubusercontent.com/40006814/162067963-21c24681-6945-4216-922e-e54ca69bfa5e.png)

Service Discovery requirement

Vital for microservice

Avoid coupling

Maintain independence

DNS is common

Tough requirement

Performance

Scalability

Clustering

Multi-cloud

Prefer simplicity

Stateless RPCs -> RPCs that do not directly modify state in a data store

![image](https://user-images.githubusercontent.com/40006814/162071070-bda1c7a9-1352-4e60-ba15-052a5749f19c.png)

![image](https://user-images.githubusercontent.com/40006814/162071555-c29497a6-1625-4061-9924-c77b864d5da8.png)

![image](https://user-images.githubusercontent.com/40006814/162072380-5de07297-15ef-4885-bb85-124587c2fa80.png)

![image](https://user-images.githubusercontent.com/40006814/162073419-1bea2b16-0e99-4653-8f2d-16b0dc2c1924.png)

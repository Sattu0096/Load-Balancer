# Deploying By Me Create a Load Balancer Website


#### Introduction to Load Balancers

A load balancer is a networking component (hardware device or software service) that distributes incoming traffic across multiple servers so that no single server is overwhelmed.
By spreading requests evenly, a load balancer improves:

⚪ Performance: Users get faster response times because work is shared.

⚪ Availability: If one server fails, the load balancer automatically directs traffic to healthy servers.

⚪ Scalability: You can add or remove servers without disrupting users.

Load balancers can work at different layers of the network stack:

⚪ Layer 4 (Transport layer): Balances traffic based on IP address and TCP/UDP ports.

⚪ Layer 7 (Application layer): Makes smarter decisions using HTTP headers, cookies, or URLs.

Common examples include cloud services like AWS Elastic Load Balancing, Nginx, HAProxy, and F5 appliances.

#### Step 1.  instance name server-a server-b server-c

<img width="1920" height="890" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/7c6d9e3f-f2da-4c72-8afc-f052b3496c73" />



Step 2. Add user data script

<img width="1913" height="867" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/487e8dc2-7e74-4797-937c-a4861180909b" />




Step 3. Launch Instance 


<img width="1918" height="878" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/91eb5d28-4acd-40ee-a111-e63f6b346b87" />



Step 4. create load balancer

<img width="1915" height="865" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/5d9e2d7c-6fa1-4e23-bd5d-314cbad8d610" />




Step 5. Add 3 instances


<img width="1920" height="864" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/6055f8d4-47d6-48f2-8bb9-cb1d9e411df3" />



Step 6 . Created load balancer instance


<img width="1915" height="864" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/ac51af82-ad78-4961-8a42-0444385a5c02" />



Step 7. 3 of 3 instances of service

<img width="1913" height="864" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/47608d39-dfeb-4819-afb0-f12d38868260" />


Step 8. Copy that DNS name 

<img width="1919" height="864" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/1211873a-9dee-4c1a-a84a-404452c47633" />


Step 9. paste in DNS name visible to Round Rabin


<img width="1729" height="973" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/821d18bd-77fb-4bcb-8eaa-14c75c7b7042" />



<img width="1729" height="973" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/9ac240ce-58c0-43d3-87bf-de9e6d752c9f" />



<img width="1729" height="973" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/a43a0f32-8afe-451d-be3b-b3f73abc17d2" />









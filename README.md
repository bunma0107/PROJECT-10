# PROJECT-10
Load Balancer Solution With Nginx and SSL/TLS

Configure Nginx As A Load Balancer

Create hosted zone
![image](https://user-images.githubusercontent.com/113097621/219196860-8c887e1c-3cb7-4999-9178-50559e4e285f.png)
![image](https://user-images.githubusercontent.com/113097621/219197280-0a163d93-7f5f-443f-bb6b-f7d179b45f14.png)

![image](https://user-images.githubusercontent.com/113097621/219197881-93c59408-10a6-4bf5-a1e3-e7d8331e3a61.png)

Add Nameservers to my Domain
![image](https://user-images.githubusercontent.com/113097621/219207924-adfb0277-1f93-4380-a634-f6abfc1c2b92.png)

Create Record pointing to Load Balancer Server
![image](https://user-images.githubusercontent.com/113097621/219209931-a338af2f-52f2-47be-b4ff-341cb37d5483.png)

Setup Nginx Server using Ubuntu 20.0 
![image](https://user-images.githubusercontent.com/113097621/219212534-7656f173-dc91-4143-8b0f-852b592352cc.png)

![image](https://user-images.githubusercontent.com/113097621/219213245-0f848738-272c-49ea-8664-7df8896bf34c.png)

Enable Nginx Service  to run
![image](https://user-images.githubusercontent.com/113097621/219213576-f8bbbdd5-2157-406b-a6f0-5e63398c6af2.png)

Check Nginx Status
![image](https://user-images.githubusercontent.com/113097621/219213829-562d39bb-4195-48d1-8713-a6e8c51e4b1b.png)

Configure Nginx LB using Web Servers’ names defined in /etc/hosts
![image](https://user-images.githubusercontent.com/113097621/219215690-06b03f7c-e112-4f2d-a8d5-55d1091683b0.png)

Restart Nginx and make sure the service is up and running
![image](https://user-images.githubusercontent.com/113097621/219216411-6da68a9f-78ff-4ea5-a389-b3986a1ec49e.png)

Remove previous sites and make sure our Nginx is properly configured
![image](https://user-images.githubusercontent.com/113097621/219216828-ced6df4e-82f5-433f-853d-c027d723f0ce.png)


Link load balancer config file to our new site
![image](https://user-images.githubusercontent.com/113097621/219218144-7f4b660a-01ca-4096-8d56-839d40ce4601.png)

![image](https://user-images.githubusercontent.com/113097621/219892486-ecd37ce8-308f-45eb-8ac3-09eb2e73d5ac.png)

![image](https://user-images.githubusercontent.com/113097621/219892305-243ccc30-962d-4553-866d-bbec47d18eab.png)

Register a new domain name and configure secured connection using SSL/TLS certificates





## F5-BIG-IP-to-NGINX-
- F5 BIG-IP to NGINX This snippet shows configures NGINX Plus to query a service registry and parse the DNS SRV records
- The service registry provides service location information in the form of a DNS SRV record. 
- A DNS SRV record differs from a standard DNS record in that it includes the port number, which is dynamically assigned. 
- The load balancer for a microservices‑based application must be able to extract the IP address and port information from the DNS SRV record provided by the service registry

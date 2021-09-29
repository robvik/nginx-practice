# nginx-practice
A practice repository for different nginx configurations for:
- Webservers
- Reverse proxies
- Load balancers

The configurations focus on:
- Performance
- Security (HTTP/2, SSL, TFS, /etc/sysctl.conf)
- Caching (including micro cache)
- Geographical access control
- Bandwidth access control

#### nginx commands
- nginx -h: shows the help menu
- nginx -v: shows the nginx version
- nginx -V: shows the nginx version, build information, and configuration arguments
- nginx -t: tests the nginx configuration
- nginx -T: tests the nginx configuration and prints the validated configuration to the screen
- nginx -s signal: Sends signals to stop, quit, reload, and reopen the nginx process

#### complete example (webserver, load balancer, reverse proxy)
![alt text](https://miro.medium.com/max/964/1*wsxdxOWkR7arPfNQNnHxzw.png "Complete architectural setup")
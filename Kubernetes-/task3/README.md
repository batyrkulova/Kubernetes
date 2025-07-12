I created a Pod named application-probe with nginx. 
I added the two end points /started and /health to aplication-probe , it game me some errors since It doesn't have built-in knowledge of /started or /health.
I configured the application-probe and asign the port 5000, it game me an error again since nginx default port is 80 and 443 and it will not work at any other ports exept this two that I meantioned previously. 

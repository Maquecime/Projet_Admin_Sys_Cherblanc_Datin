
#Admin Sys Project

This project was released as a part of our Sysadmin class during our professional degree.

The purpose of this project is to create a modern technical architecture, for the management of three simple website, and a wordpress linked to a mysql database and a phpmyadmin client.

These images are built, and passed to a proxy, which organize them into a clean network. 

Finally, we also added a load balancer between the site C1 and C. The purpose of this load balancer is to redirect either to C1 or C2, depending on the number of connections of each one (redirects to the one with the fewest connections)
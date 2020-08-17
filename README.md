# b4bylister
Use b4bydomlister Subdomain Finder In Order To Make Your Reconnaissance Process Faster And Effortless

As we know finding subdomains of a particular website let us explore the full domain infrastructure of it. Building such a tool is really handy when it comes to information gathering phase in penetration testing for ethical hackers.

Searching for subdomains manually would take forever. Luckily, we don't have to do that, in this repo, we will build a subdomain scanner in Python using requests library. Let's get started!

The method we gonna use here is brute-forcing, in other words, we gonna test all common subdomain names of that particular domain, whenever we receive a response from the server, that's an indicator for us that the subdomain is alive.

Open up a new Python file and follow along, let's use google.com for demonstration purposes, I used it because google has a lot of subdomains though:

import requests

# the domain to scan for subdomains
domain = "google.com"

After running up the entire script we can see that 
Finally, when the exception isn't raised, then the subdomain exists.
Also, consider writing the results to a file instead of just printing into the console, this will let you explore discovered subdomains later after the execution of the script.

Alright, we are done, Now you know how to discover subdomains of any website you really want!

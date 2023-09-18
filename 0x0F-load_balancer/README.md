# Load balancer :computer:

In this project, I continued to build up the configuration of the web server
issued in project 0x0B. I was issued two additional servers, one to replicate
the Nginx configuration of my original server.

## Tasks :page_with_curl:

* **0. Double the number of webservers**
  * [0-custom_http_response_header](./0-custom_http_response-header): Bash
  script that installs and configures Nginx on a server with a custom HTTP
  response header.
    * The name of the HTTP header is `X-Served-By`.
    * The value of the HTTP header is the hostname of the server.

* **1. Install your load balancer**
  * [1-install_load_balancer](./1-install_load_balancer): Bash script that
  installs and configures HAproxy version 1.5 on a server.
    * Enables management via the init script.
    * Requests are distributed using a round-robin algorithm.

## Resources
****
<a href="https://youtu.be/C2NLPQTvO9M" target="blank">Load Balancer</a>

---

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/mpfanawagacha" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="Manuel Dinis Júnior" height="30" width="40" /></a>
<a href="https://linkedin.com/in/manuel-dinis-junior" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="agboola-olawale-damilola-7b2132246" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/21437069" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="19747131" height="30" width="40" /></a>
<a href="https://instagram.com/manueldinisjunior" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Manuel Dinis Júnior" height="30" width="40" /></a>

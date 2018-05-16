## Pi-hole-Project

Pi-hole is essentially a DNS server 
This project runs the DNS service on the local network and uses the Raspberry pi as the server.
Pi-Hole takes care of the DNS resolution by proxying the DNS traffic to third-party DNS services and blocking requests that feature on its blacklist.

Part of the project looks at the DNS queries for specific sites and which sites grab the most data. 

# Getting Started

From https://github.com/pi-hole/pi-hole

For a quick install you can install following this command:
```
curl -sSL https://install.pi-hole.net | bash

```
# Alternative Methods

There are two other methods to use to download. I used the top approach because it was easier, but the next option work just as well. 

```
git clone --depth 1 https://github.com/pi-hole/pi-hole.git Pi-hole
cd "Pi-hole/automated install/"
sudo bash basic-install.sh
```

```
wget -O basic-install.sh https://install.pi-hole.net
sudo bash basic-install.sh
```

# Post Installment

After Successful installment, you will get prompts that you can just hit okay and if successful you should get a message that looks like this:

![alt text](screenshots/Pi-hole1.png "successful installment")


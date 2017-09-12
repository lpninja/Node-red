# Node-red
This is the node-red work that helps connect Raspberry Pi, Mosquitto, and IOT devices to blockchains. 
The first examples used will be with the SolarCoin blockchain.

**NR Sunfinder**

This small script that plugs directly into **Node-red** allows the user to scrape the SLR blockchain by interacting with the SLR chains inbuilt 523 character TS Message Space.

In the **ELCCv1** standard that we wrote in python we setup the protocol for the 523 character space. Then the NR sunfinder can crawl that script and find out interesting information that is being emitted to the SLR chain in real time.

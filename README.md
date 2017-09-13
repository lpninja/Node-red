# Node-red
This is the node-red work that helps connect Raspberry Pi, Arduino, Odriod, Mosquitto MQTT, and IOT devices to blockchains. 
The first examples used will be with the SolarCoin blockchain. Some later work with IOTA.

**NR Sunfinder**

The Node-red sunfinder script is designed to integrate with the SolarCoin Block Explorer at https://chainz.cryptoid.info/slr/ and extract solar PV generation data from the SolarCoin blockchain. A similar python script can also be found https://github.com/Scalextrix/ELCC/tree/master/sunfinder if you prefer python.

This small script that plugs directly into **Node-red** allows the user to scrape the SLR blockchain by interacting with the SLR chains inbuilt 523 character TX Message Space.

In the **ELCCv1** standard that we wrote in python we setup the protocol for the 523 character space. Then the NR sunfinder can crawl that script and find out interesting information that is being emitted to the SLR chain in real time.

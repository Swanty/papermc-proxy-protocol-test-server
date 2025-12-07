## PaperMC 1.21.10 server for testing Proxy Protocol

## Running
```
docker compose up
```

It will automatically download [Geyser](https://geysermc.org/download?project=geyser), [floodgate](https://geysermc.org/download?project=floodgate) and [ProxyProtocolTesting](https://github.com/Swanty/papermc-proxy-protocol-test-plugin) plugins  
This github repo also includes PaperMC config and Geyser config preconfigured for proxy protocol  
So all you have to do is just run the docker container


## Connecting

127.0.0.1:25565 - Java  
127.0.0.1:19132 - Bedrock  

Note: You won't be able to connect directly from MC client, since proxy protocol is enabled  
You have to use a proxy that connects to server using proxy protocol

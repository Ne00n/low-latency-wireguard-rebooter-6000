# low-latency-wireguard-rebooter-6000
Low Latency is king, we know that, but what if I could tell you, you could setup a script that tracks latency and restarts wireguard links automatically to drop latency? 

Technically this is a bit more complex, due to load balancing and other stuff happenning, it can be the case, that you end up on a link that has higher latency after some time.
The idea here is, to monitor the latency of each individual link and restart the wg interface to hopefully land on the better route with the lower latency again.

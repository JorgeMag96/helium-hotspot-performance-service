# Helium Hotstpot Performance Service (HHPS)
Helium Hotstpot Performance Service (HHPS) monitors hotspot witnesses by keeping the history of RSSI, SNR, distance, and frequency.

Rquirements:
  * JDK 11
  * MongoDB

TODO: planning to expose a single POST endpoint to register a hotspot for performance monitoring and a GET endpoint for retrieving the "health", the service will have a cron job that triggers once per day per registered hotspot and stores the witnesses data.
* A tool like this will make easy to spot when a hotspot starts to perform poorly in comparison to how it was previously performing in terms of quality of witnessing. OR to detect when a witness is performing poorly.

# Infocast

Stream data about any topics to infocast, and it will make sure all your clients receive it immediately over a websocket. Infocast an also store the latest event about any topic, which makes it very easy to build views that immediately start with the latest avialable data. 

Works great for a constantly changing dashboard for instance, or a map, or a price ticker, for anywhere from 10s to 100,000s of viewers. 

## Streaming Protocols

Infocast supports connecting to the streaming endpoint via regular websockets. You can then subscribe to topics and start receiving the latest events for those topics. 

## Storage

Infocast uses Redis or Postgres to store a list of events for each topic. 

## Implementation

Infocast is written in Go. 

## Ably.io Transporter

Moleculer Transporter for [Ably.io](https://www.ably.io/).
Ably's realtime APIs expose the entire Ably infrastructure to developers,
making it easy to power realtime functionality at any scale.
Ably's free "developer" plan contains 3m monthly messages,
100 peak connections and 100 peak channels.

```java
ServiceBroker broker = ServiceBroker.builder()
                                    .nodeID("node1")
                                    .transporter(new AblyTransporter("apiKey"))
                                    .build();
```

The "apiKey" role must have "Publish" and "Subscribe" privileges.
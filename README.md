## Ably.io Transporter for Moleculer Java

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

## Moleculer Documentation

[![Documentation](https://raw.githubusercontent.com/moleculer-java/site/master/docs/docs-button.png)](https://moleculer-java.github.io/site/transporters.html#centralized-transporters)

## License

This project is available under the [MIT license](https://tldrlegal.com/license/mit-license).
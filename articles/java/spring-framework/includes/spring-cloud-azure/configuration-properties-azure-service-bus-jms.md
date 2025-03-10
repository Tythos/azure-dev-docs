---
author: KarlErickson
ms.author: v-yonghuiye
ms.date: 06/29/2022
---

## Azure Service Bus JMS properties

> [!div class="mx-tdBreakAll"]
> | Property                                                     | Description                                                                                                                               |
> |--------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
> | spring.jms.servicebus.connection-string                      | Connection string to connect to a Service Bus namespace.                                                                                  |
> | spring.jms.servicebus.enabled                                | Whether to enable Servive Bus JMS autoconfiguration. The default value is `true`.                                                         |
> | spring.jms.servicebus.idle-timeout                           | Connection idle timeout duration. The default value is `30m`.                                                                             |
> | spring.jms.servicebus.listener.phase                         | The phase in which this container should be started and stopped.                                                                          |
> | spring.jms.servicebus.listener.reply-pub-sub-domain          | Whether the reply destination type is topic. Only works for the bean of topicJmsListenerContainerFactory.                                 |
> | spring.jms.servicebus.listener.reply-qos-settings            | The QosSettings to use when sending a reply.                                                                                              |
> | spring.jms.servicebus.listener.subscription-durable          | Whether to make the subscription durable. Only works for the bean of topicJmsListenerContainerFactory. The default value is `true`.       |
> | spring.jms.servicebus.listener.subscription-shared           | Whether to make the subscription shared. Only works for the bean of topicJmsListenerContainerFactory.                                     |
> | spring.jms.servicebus.password                               | Login password of the AMQP broker.                                                                                                        |
> | spring.jms.servicebus.pool.block-if-full                     | Whether to block when a connection is requested and the pool is full. Set it to false to throw a 'JMSException' instead.                  |
> | spring.jms.servicebus.pool.block-if-full-timeout             | Blocking period before throwing an exception if the pool is still full.                                                                   |
> | spring.jms.servicebus.pool.enabled                           | Whether a JmsPoolConnectionFactory should be created, instead of a regular ConnectionFactory.                                             |
> | spring.jms.servicebus.pool.idle-timeout                      | Connection idle timeout.                                                                                                                  |
> | spring.jms.servicebus.pool.max-connections                   | Maximum number of pooled connections.                                                                                                     |
> | spring.jms.servicebus.pool.max-sessions-per-connection       | Maximum number of pooled sessions per connection in the pool.                                                                             |
> | spring.jms.servicebus.pool.time-between-expiration-check     | Time to sleep between runs of the idle connection eviction thread. When negative, no idle connection eviction thread runs.                |
> | spring.jms.servicebus.pool.use-anonymous-producers           | Whether to use only one anonymous 'MessageProducer' instance. Set it to false to create one 'MessageProducer' every time one is required. |
> | spring.jms.servicebus.prefetch-policy.all                    | Fallback value for prefetch option in this Service Bus namespace. The default value is `0`.                                               |
> | spring.jms.servicebus.prefetch-policy.durable-topic-prefetch | The number of prefetch for durable topic. The default value is `0`.                                                                       |
> | spring.jms.servicebus.prefetch-policy.queue-browser-prefetch | The number of prefetch for queue browser. The default value is `0`.                                                                       |
> | spring.jms.servicebus.prefetch-policy.queue-prefetch         | The number of prefetch for queue. The default value is `0`.                                                                               |
> | spring.jms.servicebus.prefetch-policy.topic-prefetch         | The number of prefetch for topic. The default value is `0`.                                                                               |
> | spring.jms.servicebus.pricing-tier                           | Pricing tier for a Service Bus namespace.                                                                                                 |
> | spring.jms.servicebus.remote-url                             | URL of the AMQP broker. Auto-generated by default. The default value is `amqp://localhost:5672`.                                          |
> | spring.jms.servicebus.topic-client-id                        | Service Bus topic client ID. Only works for the bean of topicJmsListenerContainerFactory.                                                 |
> | spring.jms.servicebus.username                               | Login user of the AMQP broker.                                                                                                            |

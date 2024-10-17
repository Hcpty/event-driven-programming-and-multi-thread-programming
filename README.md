# Readme
A note about Event-driven Step-arranged Programming.

现实是由事件驱动、步骤编排的。一方面，对于每一个事件，其发生时刻都是未知的，另一方面，对于每一种事件，其处理步骤都是可知的。

由于发生时刻未知，所以一种自然的方式是通过事件复用器集中侦听事件，当注册事件发生时，由事件分用器来调用注册事件处理器。

因为发生时刻未知，同时还要遵守处理步骤，所以一种自然的方式在注册事件处理器中嵌套注册事件处理器。

### Credits
- [Don’t call us, we’ll call you.](https://vertx.io/docs/vertx-core/java/#_dont_call_us_well_call_you)

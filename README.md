# Readme
A note about Event-driven Step-arranged Programming.

现实是由事件驱动的，而任务是由步骤编排的。所以，应该按照事件驱动的范式进行编程，同时在注册事件处理器中反映执行任务的步骤。

事件驱动步骤编排编程的程序有两个特点：
- 第一个特点，程序中存在事件侦听器，当其侦听到注册事件发生时，要调用对应的注册事件处理器。
- 第二个特点，程序通过注册事件处理器的嵌套层次反映执行任务的步骤。

### Credits
- [Event-driven programming - Wikipedia](https://en.wikipedia.org/wiki/Event-driven_programming)

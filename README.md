# readLineFine
#按行顺序读取文件的

aaa.txt
12345
67890
我要好好学习！
node js

result：
1
12345
1
67890
1
我要好好学习！
1
node js

Stream用法详解
//所有的流都实现了EventEmitter的接口，具备事件能力，通过发射事件来反馈流的状态。比如有错误发生时会发射“error”事件，有数据可被读取时发射“data”事件。这样我们就可以注册监听器来处理某个事件，达到我们的目的。

//Node.js定义了Readable、Writable、Duplex、Transform四种流

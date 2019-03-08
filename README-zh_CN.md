# quorum-maker-nodemanager

这个工程是从[quorum-maker-nodemanager](https://github.com/synechron-finlabs/quorum-maker-nodemanager "quorum-maker-nodemanager")克隆过来的,
我把工程里面写的节点和项目的绝对路径改为了作为运行时的参数传递进去.

### 开始

克隆这个仓库:
<pre><code>git clone https://github.com/huangruzhe/quorum-maker-nodemanager
cd quorum-maker-nodemanager</code></pre>

下载这个包文件:
<pre><code>go get github.com/huangruzhe/quorum-maker-nodemanager/</code></pre>


运行程序:
<pre><code> 方法1: 直接执行语句 "go run main.go  {nodeUrl} {listenPort} {nodePath} {programPath}"
 方法2: 使用golang IDE 编辑运行时的配置项 "Program arguments"</code></pre>

参数解释
 <pre><code>nodeUrl: 节点http访问地址
listenPort: 工程启动端口
nodePath: 节点所在目录
programPath: 工程所在目录</code></pre>

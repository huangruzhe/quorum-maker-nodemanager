English | [简体中文](./README-zh_CN.md) 
# quorum-maker-nodemanager

This project is forked from [quorum-maker-nodemanager](https://github.com/synechron-finlabs/quorum-maker-nodemanager "quorum-maker-nodemanager"). I modify the node absolute path and the program absolute path as running param.

### Getting Started

Clone the repo:
<pre><code>git clone https://github.com/huangruzhe/quorum-maker-nodemanager
cd quorum-maker-nodemanager</code></pre>

Install the package :
<pre><code>go get github.com/huangruzhe/quorum-maker-nodemanager/</code></pre>


Start:
<pre><code> method1: simple run this "go run main.go  {nodeUrl} {listenPort} {nodePath} {programPath}"
 method2: Use IDE golang and edit configurations "Program arguments"</code></pre>

 expresion param
 <pre><code>nodeUrl: The node request http address
listenPort: The program running port
nodePath: The node directory path
programPath: The program directory path</code></pre>

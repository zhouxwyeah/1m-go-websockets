你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# Going Infinite, handling 1M websockets connections in Go
This repository holds the complete implementation of the examples seen in Gophercon Israel talk, 2019.

# Usage
This repository demonstrates how a very high number of websockets connections can be maintained efficiently in Linux

Everything is written in pure Go

Each folder shows an example of a server implementation that overcomes various issues raised by the OS, by the hardware or the Go runtime itself, as shown during the talk.

`setup.sh` is a wrapper to running multiple instances using Docker. See content of the script for more details of how to use it.

`destroy.sh` is a wrapper to stop all running clients. Note that it removes any running container, so use with caution.

A single client instance can be executed by running `go run client.go -conn=<# connections to establish>`

Slides are available [here](https://speakerdeck.com/eranyanay/going-infinite-handling-1m-websockets-connections-in-go)

# 认证相关 #

https://github.com/markbates/goth

[https://github.com/markbates/goth](https://github.com/markbates/goth)

Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications.


[https://github.com/goji/httpauth](https://github.com/goji/httpauth "https://github.com/goji/httpauth")

http认证中间件


# 基础组件(中间件) #

[http://www.gorillatoolkit.org/pkg/pat](http://www.gorillatoolkit.org/pkg/pat "http://www.gorillatoolkit.org/pkg/pat")

提供极简的http路由，接入方便


	func main() {
	    r := pat.New()
	    r.Get("/products", ProductsHandler)
	    r.Get("/articles", ArticlesHandler)
	    r.Get("/", HomeHandler)
		r.Get("/articles/{category}/{id:[0-9]+}", ArticleHandler)
		r.Get("/articles/{category}/", ArticlesCategoryHandler)
		r.Get("/products/{key}", ProductHandler)
	    http.Handle("/", r)
	}




[https://github.com/gorilla/handlers](https://github.com/gorilla/handlers "https://github.com/gorilla/handlers")

各种http中间件


[https://github.com/gorilla/sessions](https://github.com/gorilla/sessions "https://github.com/gorilla/sessions")

session中间件

[https://github.com/gorilla/mux](https://github.com/gorilla/mux "https://github.com/gorilla/mux")

路由组件


[https://github.com/urfave/negroni](https://github.com/urfave/negroni "https://github.com/urfave/negroni")

在Go语言里，Negroni 是一个很地道的 web 中间件，它是微型，非嵌入式，并鼓励使用原生 net/http 处理器的库。
如果你用过并喜欢 Martini 框架，但又不想框架中有太多魔幻性的特征，那 Negroni 就是你的菜了，相信它非常适合你


# 反向代理 #


[https://github.com/containous/traefik](https://github.com/containous/traefik "https://github.com/containous/traefik")

[https://traefik.io/](https://traefik.io/ "https://traefik.io/")

比nginx更强大、更灵活，内置了webui，可以查看服务状态、请求状态等

ræfik (pronounced like traffic) is a modern HTTP reverse proxy and load balancer made to deploy microservices with ease. It supports several backends (Docker, Swarm, Kubernetes, Marathon, Mesos, Consul, Etcd, Zookeeper, BoltDB, Eureka, Amazon DynamoDB, Rest API, file...) to manage its configuration automatically and dynamically.

特点

	It's fast
	No dependency hell, single binary made with go
	Rest API
	Multiple backends supported: Docker, Swarm, Kubernetes, Marathon, Mesos, Consul, Etcd, and more to come
	Watchers for backends, can listen for changes in backends to apply a new configuration automatically
	Hot-reloading of configuration. No need to restart the process
	Graceful shutdown http connections
	Circuit breakers on backends
	Round Robin, rebalancer load-balancers
	Rest Metrics
	Tiny official docker image included
	SSL backends support
	SSL frontend support (with SNI)
	Clean AngularJS Web UI
	Websocket support
	HTTP/2 support
	Retry request if network error
	Let's Encrypt support (Automatic HTTPS with renewal)
	High Availability with cluster mode





[https://github.com/xlab/android-go](https://github.com/xlab/android-go "https://github.com/xlab/android-go")

使用go语言开发Android app(主要是native app)


[https://github.com/golang-ui/nuklear](https://github.com/golang-ui/nuklear "https://github.com/golang-ui/nuklear")

golang跨平台GUI，比较小巧

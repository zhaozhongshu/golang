# 认证相关 #

https://github.com/markbates/goth

[https://github.com/markbates/goth](https://github.com/markbates/goth)

Package goth provides a simple, clean, and idiomatic way to write authentication packages for Go web applications.




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

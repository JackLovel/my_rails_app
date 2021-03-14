## 版本

```
ruby 3.0.0p0
rails 6.1.3
```

## 运行
```
$ bundle install 
$ rails webpacker:install
$ rails s 

// 开启 jit 
$ ruby --jit bin/rails s
```
## 生成镜像
```
$ cd my_rails_app
$ docker build -t app:1.0 .
```

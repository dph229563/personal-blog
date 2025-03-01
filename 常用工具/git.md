```
//查看全局配置
git config --global -l    
//设置全局用户名和邮箱
git config --global user.name "yourname"
git config --global user.email "your@email.com"
//设置当前仓库用户名和邮箱
git config user.name "username" 
git config user.email "email@email.com"
// 全局设置代理在开启shadowsocks的前提下
git config --global http.proxy http://127.0.0.1:1080
git config --global https.proxy http://127.0.0.1:1080
// 全局关闭代理
git config --global --unset http.proxy
git config --global --unset https.proxy
```
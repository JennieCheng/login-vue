#使用github为server的vue前端  
##配置文件位于：src/config/config.js
包括授权地址、accessToken获取地址、用户信息请求地址、clientId、clientSecret
##用户登录和获取accessToken
>1.src/util/loginUtils.js
登录，配置客户端重定向到认证地址，等待授权--->login:function
>2.src/components/sslogin.vue
取得授权码，取得accessToken---->mounted
##获取身份信息
使用accessToken，getUserInfo


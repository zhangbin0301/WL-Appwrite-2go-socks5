# 提示:

1.不要选择nodejs模板，选择导入仓库部署

2.部署命令改成npm install

3.进入网站添加变量TUNNEL_PROXY=1，Joye里面打开Any权限，设置定时任务，过期时间调到最大

4.redeploy,然后点excute

5.打开网址查看是否出现网页，出现则部署正常



//开启socks5代理，应对封锁隧道的容器。 在appwrite 设置--Environment variables--添加变量TUNNEL_PROXY
//TUNNEL_PROXY="1"  //1是使用免费的socks5,可能不稳定和速度慢。  
//TUNNEL_PROXY="socks5://用户名:密码@ip:端口" //也可使用自己的，格式socks5://用户名:密码@ip:端口，可以多个，每个用空格隔开

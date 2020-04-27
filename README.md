# static-server

自己写一个静态服务器

# 启动静态服务器

node server.js 8888

此种方法存在一个缺点：每次更改server.js，都需要重新启动，所以采用以下方法

node-dev server.js 8888


# 关于server.js和server1.js

server.js是对server1.js更好的封装.在server.js中，不需要每次添加新的路由，因为对路径做了一个封装。


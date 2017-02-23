# face2error
		ErrorInspector 
		ErrorInspector.Config must before at all where you need to inspect 

### face2error 服务原理
		前台页面调用ErrorInspector.js将拦截到的错误详细信息发送到后台日志服务(node + mongodb)     
		存储在数据仓库中, 并且通过socketio 将错误实时显示在后台日志查询页面上。


### 后台服务部署说明 
* npm install 
* npm start
* 启动mongodb 服务
		访问 localhost:2333/a.html  












You can login maccms backstage
according to 视频 -> 添加视频 on 截图 Input box insert xss payload "<img src=x onerror="alert(document.cookie)">" and save
then according to 系统 -> 开放API设置 -> start 接口开关
and go to visit http://127.0.0.1/api.php/provide/vod/?ac=list

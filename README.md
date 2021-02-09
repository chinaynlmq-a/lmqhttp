# lmqhttp
对axios对二次封装

# github
 https://github.com/chinaynlmq-a/lmqhttp.git

 # 补充相关依赖包

 # 安装 
 npm i lmqhttp
 # 使用
 ```javascript
  import http from 'lmqhttp';
   http({
        url:'url-address',
        method: 'post'
        }).then(data=>{
          // 接口返回的参数
          console.log(data);
        });
    }
 ``` 
 # 封装axios在实际开发中的作用
 - 对项目对异常统一处理
 - 和服务端约定好对状态数据
 - 返回数据处理只返回有用的数据
 - 统一升级 比如axios 升级 只用升级一个文件
 - 添加loading效果，一次处理


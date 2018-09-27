# APIJSON 在node.js上的实验报告
        
Steps to run this project:

1. 运行 `yarn i` 和 `npm i -g ts-node`.
2. 设置数据库 `ormconfig.json`
3. 在vscode上 执行快捷键ctrl+shift+p 输入 Toggle Auto  Attach， 启用自动附加。然后在vscode 命令行中运行 `yarn nodemon`
4. 发送请求 GET /users 初始化数据
5. 测试 POST /apijson 
```json
    {
        "[]":{
            "User":{
                "id":1
            },
            "Message":{
                "id":1
            }
        }
    }
```

敏捷web开发作业之spring boot

[网址](https://school.thoughtworks.cn/learn/program-center/subjectiveQuiz/index.html#/student/program/195/task/3111/assignment/4214/quiz/1300)

Todo list
使用SpringBoot框架，构建一个Restful API，能够完成Todo list的以下功能。
* 返回所有Todo任务
* 创建一个新的Todo任务
* 返回一个指定ID的Todo任务
* 删除一个Todo任务

为简化流程，不引入数据存储，即，不需要做数据持久化，可以在服务器运行时满足功能即可。

Todo中一个任务的JSON格式定义为：

```json
  {
    "id": 1,
    "content": "Restful API homework",
    "createdTime": "2019-05-15T00:00:00Z"
  }
```

进一步的功能提示：需完成的四个功能的Restful API定义如下，实现即可。

GET /api/tasks/

POST /api/tasks/

GET /api/tasks/{id}
 
DELETE /api/tasks/{id}
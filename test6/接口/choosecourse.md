# 接口：choosecourse [返回](https://github.com/caiweicai/is_analysis/tree/master/test6/README.md)

用例： [课程选择](https://github.com/caiweicai/is_analysis/tree/master/test6/用例/课程选择.md)

- 功能： 修改（设置）用户的密码。

- 权限： 学生/老师：修改自己的密码，必须先登录。

- API请求地址： 接口基本地址/v1/api/choosecourse

- 请求方式 ： POST

- 请求实例：

  ```
    {
        "courseNo":1234,
        "course_name":AF#W@#AAAASDF
        "addtime":2015.5.1 12:23:11
    }
  ```

- 请求参数说明:

  | 参数名称    | 说明           |
  | ----------- | -------------- |
  | courseNo    | 课程编号       |
  | course_name | 课程名称       |
  | addtime     | 增加课程的时间 |

  返回实例：

  ```
    {         
        "status": true,
        "info": null,    

    }
  ```

  返回参数说明：

| 参数名称 | 说明                                          |
| -------- | --------------------------------------------- |
| status   | bool类型，true表示正确的返回，false表示有错误 |
| info     | 返回结果说明信息                              |


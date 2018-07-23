## 账号中心
### 统一的c端账户登录中心
### 统一的账户管理系统
---
#### 查询
##### 单个用户详情
* 接口名称
> getUserInfo
* 接口请求参数
```
    {
        'app_id':'',//必传
        'user_id:'',//选传
        'phone':'',//选传
        'universal_union_id':'',//选传
        'wx_nickname':'',//选传
        'info_filed':[]//获取列表
    }
```
* 接口预计返回数据
```
    {
        'app_id':'',
        'user_id':'',
        'phone':'',
        'universal_union_id':'',
        'wx_nickname':'',
        .
        .
        .
    }
```
##### 获取用户列表
* 接口名称
> getUserList
* 接口请求参数
```
    {
        'app_id':'',//必传
        'user_id:[],//选传
        'phone':[],//选传
        'universal_union_id':[],//选传
        'wx_nickname':[],//选传
        'info_filed':[]//获取列表
    }
```
* 接口预计返回数据
```
    [
        {
            'app_id':'',
            'user_id':'',
            'phone':'',
            'universal_union_id':'',
            'wx_nickname':'',
            .
            .
            .
        }
    ]
    
```
##### 获取用户总数
* 接口名称
> getUserCount
* 接口请求参数
```
    {
        'app_id':''//必传
    }
```
* 接口预计返回数据
```
    {
        'count':0
    }
```

---
#### 创建
##### 批量导入
* 接口名称
> insertUserList
* 接口请求参数
```
[
    {
        'app_id':'',//必传
        'user_id:'',//选传
        'phone':'',//选传
        'universal_union_id':'',//选传
        'wx_nickname':'',//选传
        'info_filed':[]//获取列表
    }
]
```
* 接口预计返回数据
```
    {
        
    }
```
##### 创建单个用户
* 接口名称
> createUserInfo
* 接口请求参数
```
    {
        'app_id':'',//必传
        'user_id:'',//选传
        'phone':'',//选传
        'universal_union_id':'',//选传
        'wx_nickname':'',//选传
        'info_filed':[]//获取列表
    }
```
* 接口预计返回数据
```
    {
        'app_id':'',
        'user_id':'',
        'phone':'',
        'universal_union_id':'',
        'wx_nickname':'',
        .
        .
        .
    }
```

---

#### 更新
##### 单个用户更新
* 接口名称
> updateUserInfo
* 接口请求参数
```
    {
        'app_id':'',//必传
        'user_id:'',//选传
        'phone':'',//选传
        'universal_union_id':'',//选传
        'wx_nickname':'',//选传
        'info_filed':[]//获取列表
    }
```
* 接口预计返回数据
```
    {
        'app_id':'',
        'user_id':'',
        'phone':'',
        'universal_union_id':'',
        'wx_nickname':'',
        .
        .
        .
    }
```
##### 批量更新
---
title: API Reference

language_tabs:
  - ruby

toc_footers:
  - <a href='http://github.com/tripit/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# 介绍

API 文档

1.1## 获取用户信息

1.2## V1

1、3## HTTP 请求

`GET http://my-site/api/v1/users/<id>`

1.4## 请求参数

参数名 | 是否必需 | 描述
--------- | ------- | -----------
id | 是 | 用户 id

1.5## 响应

```json
{
  "user":
  {
    "id": 1,
    "email": "test-user-00@mail.com",
    "name": "test-user-00",
    "activated": "2016-11-15T14:42:24.697Z",
    "admin": false,
    "created_at": "2016-11-15T14:42:24.697Z",
    "updated_at": "2016-11-15T14:42:24.697Z",
  }
}
```

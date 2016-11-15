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

# 获取用户信息

## V1

## HTTP 请求

`GET http://my-site/api/v1/users/<id>`

## 请求参数

参数名 | 是否必需 | 描述
--------- | ------- | -----------
id | 是 | 用户 id

## 响应

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

This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

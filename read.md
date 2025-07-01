# 简历生成模版
本人审美不好，不想花太多时间去写，所以用模版来生成简历
## 技术栈
- node
- ant design开发
- react 
- tailwindcss
- next.js
- jspdf

- 存储方式：indexDB
- 保存方式，json导入导出
- 周期：一周
## 功能
- 个人信息模块
- 教育信息
- 技能模块
- 工作信息
- 项目信息
- 社交媒体
- 自我介绍
- 语言
## 数据格式
```
{
    "user": {
        "photo": "",
        "name": "",
        "address": "",
        "job": ""，
        "sexx":""
    },
    "education":{
        "title": "",
        "list": [
            {
                "date": "",
                "school": "",
                "major": "",
                "introduction": ""
            }
        ]
    },
    "skill":{
        "title": "",
        "list": [
            {
                "skillName": "",
                "skillExplain": []
            }
        ]
    },
    "work":{
        "title": "",
        "list": [
            {
                "companyName": "",
                "job": "",
                "date": "",
                "skillExplain": []
            }
        ]
    },
    "project":{ 
        "title": "",
        "list": [
            {
                "projectName": "",
                "job": "",
                "duty": [
                    {
                        "title": "",
                        "content": ""
                    }
                ]
            }
        ]
    },
    "introduction": "",
    "language": {
        "name": "",
        "level": "",
        "explain": ""
    },
    "Social": {
        "name": "",
        "way": ""
    }
}
```
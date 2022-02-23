## 自用API地址
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fzkeq%2Ficodeq-api.svg?type=small)](https://app.fossa.com/projects/git%2Bgithub.com%2Fzkeq%2Ficodeq-api?ref=badge_small)


### 视频解析 `/api/movie`

🚀 花了几小时写的视频解析接口

🚀 特性：实时生成，只要有数据返回就可以看

🚀 首页的解析链接各大平台均可用

🚀 推荐使用电脑访问

🚀 使用方法：使用首页链接或在网址后加问号加关键词搜索

🚀 地址：https://api.icodeq.com/api/movie

------------

### Github 日历 `/api/github`

🚀 原项目地址： https://github.com/Zfour/python_github_calendar_api

------------

### ~图欧君学习资源库短链服务 `/api/tuostudy`~

🚀 ~原理是爬虫读我的 `oss` 上面的 `json` 文件~

🚀 ~然后 `js`  `window.location.replace("/")`~

### 短链服务已成立分支仓库

🚀 https://github.com/zkeq/Tuostudy-Short-url

### `Notion` `database` 做数据库 `api`

🚀 仓库地址：https://github.com/zkeq/Tuostudy-Short-url/tree/main/api/notion-back-json

🚀 示例地址：https://tuo.icodeq.com/api/notion-back-json

### `Weibo` 直链转换 `API`

🚀 仓库地址：https://github.com/zkeq/icodeq-api/tree/main/api/weibo_307_video

🚀 示例地址：https://api.icodeq.com/api/weibo_307_video/

🚀 本项目由两部分组成，并且数据库基于 `redis`

🚀 `/api/weibo_307_video` 目录下的 `index.py` 是主要文件

🚀 它会去读取 `redis` 上面的 `video` 的值。

🚀 而 `/api/weibo_307_video/get-new-url` 则负责传递 `video` 的值，每次访问都会传递。

🚀 所以需要将 `SCF_30_min_fresh.py` 部署至云函数，设置半小时刷新一次（每半小时请求一次刷新）

🚀 使用说明为修改成自己的 `redis`，修改自己的视频 ID 定位。



## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fzkeq%2Ficodeq-api.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fzkeq%2Ficodeq-api?ref=badge_large)

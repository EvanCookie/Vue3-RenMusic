## RenMusic

RenMusic 是一款基于vue3的在线音乐播放器，具有音乐搜索、播放、歌词显示、播放历史、查看歌曲评论等功能

![](./images/index.png)

## 免责声明

1. **无担保声明**：本项目只是一个前端练手的项目，旨在vue3学习阶段能提升自己的技能水平和对前端技术的理解。不提供任何音频存储和贩卖服务。所有音频内容均由网易云音乐的第三方 API 提供，仅供个人学习研究使用，严禁将其用于任何商业及非法用途，版权归原始平台所有。
2. **使用风险自担**：使用本项目造成的任何纠纷、责任或损失由使用者自行承担。本项目开发者不对因使用本项目而产生的任何直接或间接责任承担责任，并保留追究使用者违法行为的权利。
3. **第三方依赖**：本项目可能包含对第三方软件、库、服务或数据的引用或依赖。这些第三方组件可能受各自的许可协议和免责条款约束。用户在使用这些第三方组件时，应遵守相应的许可协议和免责条款，并自行承担相关风险。
4. **法律合规性**：在使用本项目时遵守相关法律法规，不得将本项目用于任何商业及非法用途。如有违反，一切后果由使用者自负。同时，使用者应该自行承担因使用本项目而带来的风险和责任。
5. **修改和分发**：用户有权根据本项目所选的开源许可证的条款修改和分发本项目的内容。然而，这种修改和分发行为应遵守相应的许可协议，并不得损害维护者或其他贡献者的合法权益。
6. **其它**: 本项目使用了网易云音乐的[第三方 API 服务](https://github.com/Binaryify/NeteaseCloudMusicApi)，对于该第三方 API 服务造成的任何问题，本项目开发者不承担责任。

请在使用本项目之前仔细阅读以上免责声明，并确保您已完全理解并接受其中的所有条款和条件。如果您不同意或无法遵守这些规定，请不要使用本项目。

## 安装与使用

### RenMusic

```bash
# 下载项目
git clone https://github.com/EvanCookie/online-music.git

# 进入项目目录
cd online-music

# 安装依赖
pnpm install

# 本地运行
pnpm dev

# 打包
pnpm build

# 预览打包
pnpm preview
```

### 后台 api 服务（本地）

[网易云音乐 NodeJS 版 API](https://github.com/Binaryify/NeteaseCloudMusicApi)

```bash
# 下载 neteasecloudmusicapi
git clone --depth=1 https://gitlab.com/Binaryify/neteasecloudmusicapi.git

# 进入 neteasecloudmusicapi 后台服务目录
cd neteasecloudmusicapi

# 安装依赖
npm install

# 运行后台 api 服务 默认 http://localhost:3000
node app.js
# 或者
npm start
```



## 技术栈

- Vite（构建工具）
- Vue3 （核心框架）
- Vue Router（路由）
- Pinia （状态管理）
- Sass （CSS预处理器）
- Axios （网络请求）
- Arco Design（组件库）



## License

[The MIT License (MIT)](https://github.com/EvanCookie/online-music/blob/master/LICENSE)

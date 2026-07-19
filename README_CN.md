# iBai

**一个 App，连接你的全部自建媒体。**

iBai 是一款原生 Apple 平台客户端，可在同一款 SwiftUI 应用中访问自建音乐、有声书与视频库。支持 Navidrome、Audiobookshelf、Emby、Plex、WebDAV、SMB、Google Drive、Dropbox 等，覆盖 iPhone、iPad、Mac 与 Apple TV。

---

## 功能特性

### 音乐

- **Navidrome** — 完整 Subsonic API 支持，连接自建音乐库
- 浏览歌单、艺术家、专辑与歌曲
- **Daily Mix**、**Genre Mix** 与电台式推荐
- 全屏播放器：同步 **歌词**、相似歌曲推荐、收藏
- 播放队列：历史记录、保存队列、随机 / 循环模式
- **离线音乐缓存**，无网络也可播放
- **Scrobble** 至 [Last.fm](https://www.last.fm/) 与 [ListenBrainz](https://listenbrainz.org/)
- 锁屏、控制中心与 **CarPlay** 远程控制

### 有声书

- **Audiobookshelf** 集成
- 书库浏览与搜索
- **离线下载**，支持进度跟踪
- 与音乐共用播放器

### 视频

- **Emby**、**Plex**、**WebDAV**、**SMB**、**Google Drive**、**Dropbox**
- 多服务器配置，各自独立鉴权
- 发现页：继续观看、最近添加、推荐等
- 剧集 / 季导航，断点续播
- **离线视频下载**
- 基于 **FFmpeg**，格式支持广泛
- 内置本地 HTTP 代理，优化远程流媒体播放

### 通用

- 原生支持 **iOS**、**iPadOS**、**macOS**、**tvOS**
- 浅色 / 深色 / 跟随系统主题
- 应用内语言：English、简体中文、繁体中文（香港 & 台湾）
- 图片、音乐、有声书、视频缓存管理
- 凭据存储于系统 **Keychain**

---

## 支持平台

| 平台         | 最低版本   |
| ------       | ---------- |
| iOS / iPadOS | 18.6       |
| macOS        | 14.0       |
| tvOS         | 17.0       |

---

## 支持的服务

| 类别     | 服务                                                    | 状态   |
| ------   | ------                                                  | ------ |
| 音乐     | [Navidrome](https://www.navidrome.org/)（Subsonic API） | 已支持 |
| 有声书   | [Audiobookshelf](https://www.audiobookshelf.org/)       | 已支持 |
| 视频     | [Emby](https://emby.media/)                             | 已支持 |
| 视频     | [Plex](https://www.plex.tv/)                            | 已支持 |
| 视频     | WebDAV                                                  | 已支持 |
| 视频     | SMB / NAS                                               | 已支持 |
| 视频     | Google Drive                                            | 已支持 |
| 视频     | Dropbox                                                 | 已支持 |
| Scrobble | Last.fm、ListenBrainz                                   | 已支持 |

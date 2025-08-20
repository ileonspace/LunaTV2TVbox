# LunaTV2 TVBox api接口转换系统  

**LunaTV2 TVBox** 是一个开源的 IPTV 流媒体播放器，专为智能电视、Android TV、TVBox、手机和电脑设计。它提供超过 2000 个直播频道和 40,000 部电影、电视剧，支持 M3U、Xtream Codes 等流媒体协议，带来流畅的高质量观看体验。

## 功能特性

- **多平台支持**：兼容 Android TV、Smart TV、TVBox、手机和电脑。
- **丰富内容**：提供 2000+ 直播频道和 40,000+ 电影、电视剧。
- **即时访问**：通过激活代码快速访问内容，附带详细安装手册。
- **易于使用**：支持 M3U 播放列表和 Xtream Codes，配置简单。
- **高画质**：支持 4K、FHD 和 SD 画质，适配不同网络环境。
- **多协议支持**：兼容 M3U、M3U8、Xtream Codes 等格式。

## 安装指南

### 前提条件
- **设备**：Android 5.0+ 的智能电视、TVBox、手机或电脑。
- **网络**：建议 10Mbps 以上稳定网络连接。
- **存储**：至少 500MB 可用空间。

### 安装步骤
1. **下载应用**：
   - 从 [官方网站](https://lunatv2.example.com) 或本仓库的 [Releases](https://github.com/yourusername/lunatv2-tvbox/releases) 下载最新 APK 文件。
2. **安装 APK**：
   - 在 Android 设备上启用“允许未知来源”设置。
   - 使用文件管理器找到下载的 APK 文件，点击安装。
3. **激活服务**：
   - 打开应用，输入通过购买获得的激活代码。
   - 按照应用内提示完成配置。
4. **配置播放列表**：
   - 支持导入 M3U 或 Xtream Codes。
   - 示例 M3U URL: `http://example.com:8080/get.php?username=example&password=example&type=m3u_plus`
5. **开始使用**：
   - 浏览频道列表，享受直播或点播内容。

## 使用说明

1. **添加播放列表**：
   - 进入设置，点击“添加播放列表”。
   - 输入 M3U URL 或 Xtream Codes（用户名、密码、服务器地址）。
2. **切换画质**：
   - 在播放器中选择 4K、FHD 或 SD 画质。
3. **更新内容**：
   - 定期重新导入播放列表以获取最新频道和内容。

## 构建与开发

### 环境要求
- Android Studio 4.0 或更高版本
- Java 8 或 Kotlin
- Gradle 7.0 或更高版本

### 构建步骤
1. 克隆仓库：
   ```bash
   git clone https://github.com/yourusername/lunatv2-tvbox.git
打开项目：使用 Android Studio 打开项目文件夹。

构建项目：点击 Build > Make Project，或运行以下命令：bash

./gradlew build

运行应用：连接 Android 设备或使用模拟器，点击 Run > Run 'app'。

贡献我们欢迎社区贡献！请按照以下步骤参与：Fork 本仓库。
创建您的功能分支：bash

git checkout -b feature/your-feature

提交更改：bash

git commit -m "Add your feature"

推送到远程分支：bash

git push origin feature/your-feature

提交 Pull Request，详细描述您的更改。

请确保遵循 贡献指南 (CONTRIBUTING.md) 和 行为准则 (CODE_OF_CONDUCT.md)。常见问题 (FAQ)激活代码无效怎么办？确保输入正确的代码，或联系支持团队（support@lunatv2.example.com）。

支持哪些设备？支持 Android 5.0+ 的智能电视、TVBox、手机和电脑。

如何更新播放列表？在应用设置中重新导入最新的 M3U URL 或 Xtream Codes。

许可协议本项目采用 MIT 许可证 (LICENSE)。详情请查看许可证文件。联系我们官网: LunaTV2
支持邮箱: support@lunatv2.example.com
社区: GitHub Discussions

   

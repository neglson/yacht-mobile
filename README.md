# 游艇建造系统 - Android App

## GitHub Actions 自动构建

### 使用步骤：

1. **创建 GitHub 仓库**
   - 登录 https://github.com
   - 新建仓库，命名为 yacht-mobile

2. **推送代码到 GitHub**
   Initialized empty Git repository in /root/.openclaw/workspace/.git/

3. **触发自动构建**
   - 推送到 main 分支会自动触发构建
   - 或手动触发：Actions → Build Android APK → Run workflow

4. **下载 APK**
   - 等待约 5-10 分钟构建完成
   - 进入 Actions → 选择最新的 workflow
   - 滚动到 Artifacts 部分
   - 下载 YachtMobile-APK.zip
   - 解压得到 app-debug.apk

### 安装到手机：


### 配置信息：
- 包名：com.yacht.building
- API地址：http://47.107.59.213:3003
- 默认账号：admin / admin123

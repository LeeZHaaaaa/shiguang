【拾光 · 安卓 App 打包说明】

这是一个完整的 Android 工程（WebView 外壳 + 你的学习打卡页面），
在 Android Studio 里打开即可打包成 APK 安装到手机。

一、电脑上打包（推荐，一次搞定）
1. 下载并安装 Android Studio：
   https://developer.android.com/studio
2. 打开 Android Studio，选择「Open」，选中本文件夹「拾光App」。
3. 等它自动下载依赖和 SDK（第一次较慢，耐心等）。
4. 顶部点「Build」→「Build Bundle(s)/APK(s)」→「Build APK(s)」。
5. 完成后右下角会提示 APK 路径（app/build/outputs/apk/debug/app-debug.apk）。
6. 把 app-debug.apk 传到手机安装即可（允许安装未知来源）。

二、手机直接运行（需要有电脑连着手机）
1. 手机开启「开发者选项 → USB 调试」。
2. 用数据线连电脑，Android Studio 点绿色「Run ▶」。
3. 选择你的手机，会自动安装并打开。

三、常见问题
- 提示 Gradle 版本：点 Android Studio 推荐/默认即可。
- 提示 SDK 缺失：Android Studio 会引导你下载，一路同意。
- 打包失败：把报错截图发我，我帮你看。

说明：这个 APK 里已经内置了「今日计划、打卡、日历、统计、英语3500词、
错题本、成绩、目标、报告、AI教练、番茄钟、系统通知」等全部功能，
数据保存在手机本地。

# QQ.dsh-qqbot
QQ机器人官方dsh-qqbot优化版本
基于dsh-qqbot(https://github.com/tencent-connect/dsh-qqbot?utm_source=chatgpt.com )项目，主要为UI，网络搜索，识图，自动判断是否对话（全量）等工具，详细效果展示<img width="576" height="1280" alt="68e78f4996c648ba1994e3f8d22e5db5" src="https://github.com/user-attachments/assets/bc0635b0-8d55-4bb6-a47b-8b64557c03e9" />

#UI视频展示：


https://github.com/user-attachments/assets/eaaffb08-37a2-442f-a31f-e3eba252700b





#使用方法:
1.安装环境：
```
https://git-scm.com/install/windows
https://www.python.org/downloads/release/python-31311/
https://nodejs.org/zh-cn
https://pnpm.io/zh/installation
```
2.安装deepseek-harness
```
git clone https://github.com/deepseek-ai/deepseek-harness.git
cd deepseek-harness
pnpm install
pnpm run build
pnpm dsh web
```
3.安装插件
```
pnpm dsh plugin --profile qqbot add "目录\插件名称"
示例：pnpm dsh plugin --profile qqbot add "D:\d\dsh-qqbot-user-reference-1.0.32.tgz.tar"
注意：需要在deepseek-harness目录下使用
```
示例：
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b42b23ee-96c5-445f-b8e7-c6cfabb9e4f4" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1eebfd69-cfae-4878-afea-483ae87da951" />
4.运行
```
pnpm dsh --profile qqbot
```
其他：


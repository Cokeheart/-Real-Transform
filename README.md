睿奥同声传译 Real Transform
> 一只阔乐菌出品 —— 高效的本地同声传译/语音翻译桌面应用
项目简介
本项目是一个基于 PyQt6、faster-whisper、CUDA/cuDNN 的本地同声传译工具，支持实时语音识别与翻译，适合会议、直播、学习等多场景使用。
支持多种模型（base/small/medium/large），可自定义音频输入、降噪、历史记录等功能。

下载链接：https://www.123865.com/s/6MwiVv-wEi4H提取码:5plq

主要特性
本地运行，无需联网，保护隐私
支持多种 Whisper 模型，兼容 CUDA 加速
实时语音识别与翻译
支持历史记录与永久保存
支持系统托盘、热键操作
支持多种音频输入与降噪
支持静默启动与后台日志调试
目录结构
Apply to run_with_cud...
部署与运行
1. 环境依赖
Windows 10/11
Python 3.10+（推荐用 Anaconda 或 venv 虚拟环境）
CUDA 11.8+（如需 GPU 加速）
cuDNN 8.x+（如需 GPU 加速）
2. Python 依赖包
如果你需要源码开发或自定义打包，需安装以下依赖：
Apply to run_with_cud...
Run
requirements.txt 示例：
Apply to run_with_cud...
> 依赖包版本请根据实际开发环境调整。
3. CUDA/cuDNN 配置
安装 CUDA Toolkit（如 C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.1）
安装 cuDNN，并将 cudnn_ops64_9.dll 等 DLL 放在 exe 同目录或系统 PATH 路径下
4. Whisper 模型
下载所需的 Whisper 模型（base/small/medium/large），放入 models/ 目录下，结构如：
Apply to run_with_cud...
5. 运行方式
调试模式（带命令行窗口）：
Apply to run_with_cud...
用户模式（静默启动）：
Apply to run_with_cud...
日志和报错信息会写入 log.txt
常见问题
找不到 cudnn_ops64_9.dll？
请确保 DLL 在 exe 同目录、venv\Scripts 或已加入系统 PATH。
模型加载慢？
建议使用 GPU 加速，并选择合适的模型大小。
如何自定义配置？
编辑 config.json 文件，调整参数。
开发与打包
如需自行开发或重新打包：
Apply to run_with_cud...
Run
License
本项目仅供学习与交流，禁止用于商业用途。
如需定制或商业授权，请联系作者。
如需更详细的说明或有特殊需求，请补充说明！
<img width="1661" height="502" alt="7776a296a4a3e1c33b9f58d424acd35" src="https://github.com/user-attachments/assets/e12b76da-c6bd-4f1b-a195-8480d89da0af" />
<img width="1688" height="562" alt="b4974fe3812590aac098ddcce683083" src="https://github.com/user-attachments/assets/deea78fc-b6cd-45e5-997e-d1cc7abbf08a" />
<img width="1723" height="560" alt="0ec0e7de486583ee83c8b881335ecb8" src="https://github.com/user-attachments/assets/55d137bb-c2f2-422a-89da-cbbd57edcbbc" />
<img width="1723" height="569" alt="b9e827051dcad65643ab3a3a4bd426c" src="https://github.com/user-attachments/assets/7d0d26a8-9348-442a-8e51-4008a7b72d22" />
<img width="1685" height="688" alt="d107dbaa35d165e5f59407a266427e7" src="https://github.com/user-attachments/assets/b8739a00-3a72-453d-9591-d2eaa4797cb8" />
<img width="1723" height="560" alt="da89d8c066c61e40d9ec9d4258de910" src="https://github.com/user-attachments/assets/e829235d-255a-4866-9719-81a392d8d502" />
<img width="1641" height="852" alt="ae96fb56e8532ffb247593c4b5b98a4" src="https://github.com/user-attachments/assets/d2bd6b44-07e9-42f7-aaf2-d060372104ee" />
<img width="1687" height="740" alt="09cbe56c2d737467a6919830d173759" src="https://github.com/user-attachments/assets/7d5896c7-7644-4734-8852-e209f225a558" />








# VideoLingo-OneClick
VideoLingo + Index-TTS 批量全自动视频翻译配音加字幕软件，免安装一键启动整合包

### 2025-12-07 新增index-tts声音克隆语音合成功能，实现分角色配音

### 2026-02-04 更新edge-tts接口，优化index-tts

### 2026-04-12 更新至3.0.1，修复已知bug，整合包新增批量处理功能

## VideoLingo软件说明
VideoLingo 是一站式视频翻译本地化配音工具，能够一键生成 Netflix 级别的高质量字幕，告别生硬机翻，告别多行字幕，还能加上高质量的克隆配音，让全世界的知识能够跨越语言的障碍共享。

翻译工具采用deepseek、openai等大语言模型，让翻译结果更准确

主要特点和功能：

🎥 使用 yt-dlp 从 Youtube 链接下载视频
🎙️ 使用 WhisperX 进行单词级和低幻觉字幕识别
📝 使用 NLP 和 AI 进行字幕分割
📚 自定义 + AI 生成术语库，保证翻译连贯性
🔄 三步直译、反思、意译，实现影视级翻译质量
✅ 按照 Netflix 标准检查单行长度，绝无双行字幕
🗣️ 支持 GPT-SoVITS、Azure、OpenAI 等多种配音方案
🚀 一键启动，在 streamlit 中一键出片
🌍 多语言支持就绪的 streamlit UI
📝 详细记录每步操作日志，支持随时中断和恢复进度
与同类项目相比的优势：绝无多行字幕，最佳的翻译质量，无缝的配音体验

为方便大家快速上手体验，省去安装部署耗时，我制作了最新版免安装一键启动整合包

## VideoLingo整合包使用说明
首先到网盘内把软件压缩包下载到本地电脑上并解压，然后双击【启动软件.exe】。稍等片刻会打开webUI操作界面。

启动时会首先初始化载入模型，请耐心等待

翻译工具使用的大语言模型，需要填写API key。兼容openai的都可以。

如果你还没有API的话，可以点击下方链接免费费申请

[申请API KEY>>](https://console.compshare.cn/light-gpu/api-keys?referral_code=FlfHWpg22A9EnXni6kYKRv)

配音设置里推荐使用index-tts,声音自然，效果好，支持声音克隆，可实现分角色配音

电脑配置低可使用edge_tts，这是微软的在线文字转语音工具，云端生成，速度快，

软件设置完成后，就可以在右侧上传视频进行操作了。

## 批量视频翻译

<img width="562" height="380" alt="image" src="https://github.com/user-attachments/assets/c23d64bb-05b3-4a3b-9ce5-9f9b4fcd8177" />

有些用户用量非常大，一次需要翻译几十甚至更多视频，在页面上挨个手动操作显然效率太低，所以整合包新增了批量功能。

可以在输入框内输入youtube视频链接每行一个，或是本地视频所在文件夹路径

如果是填视频URL的话，确保你的IP是干净的，防止批量下载触发Google机器人验证，导致下载失败任务终止，所以还是建议手动将视频下载到本地文件夹，输入框里输入文件夹路径

原语言：en，zh，es，ru，fr，de，it，ja

目标语言：用自然语言描述，如简体中文，英语，法语，俄语等等

启用配音：不勾选的话只为视频加翻译字幕，勾选后生成配音视频

处理完成后生成结果保存在batch文件夹下的output文件夹内，以视频文件名命名的每个文件夹

<strong>使用批量功能前请务必先在页面上完成一次有效的单视频翻译，也就是确保你的所有配置信息都是有效的，然后才可以使用批量功能</strong>

视频教程：https://www.youtube.com/watch?v=jB5-flxJXsk
## 注意事项
英伟达显卡显存6G以上

电脑系统需要win10或11

软件运行路径中不能有空格和非英文字符

使用前先将英伟达显卡驱动更新到最新

## VideoLingo视频翻译免安装一键启动整合包下载链接

https://nuowa.net/1697

## 原项目链接

https://github.com/Huanshere/VideoLingo

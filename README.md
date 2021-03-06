﻿灵云智能输入法（Android版）
============================

灵云智能输入法是北京捷通华声语音技术有限公司自主研发的输入法软件，手写输入采用了灵云平台HWR能力，手写输入支持竖屏叠写，横屏行写，识别速度快，识别率高达99%，让用户在点触间享受到人机交互的魅力。语音输入采用了灵云平台ASR能力，输入快速准确。
如果您对灵云智能输入法有什么好的建议或意见，欢迎与我们联系。

 
如何使用
============
1. 首先需要checkout出项目。[https://github.com/open-sinovoice/sinovoice-pathfinder.git](https://github.com/open-sinovoice/sinovoice-pathfinder.git)
2. 访问灵云开放平台&灵云开发者社区：[http://www.hcicloud.com/](http://www.hcicloud.com/)，注册账号并创建一个应用。获取DeveloperKey，AppKey，CloudUrl值，申请时要点选所需能力（hwr.local.freestylus，asr.cloud.freetalk）。
3. 在IDE开发工具中导入Pathfinder工程，将DeveloperKey，AppKey，CloudUrl的值填写在Pathfinder工程中com.sinovoice.pathfinder.hcicloud.sys.SysConfig.java类中对应字段。
4. 在IDE中编译运行，确保调试终端可以正常访问网络，获取到灵云能力的授权，即可在调试终端查看和使用该输入法。

特殊Android系统
=================
在MIUI系统上，需要进行设置才可以正常使用语音识别功能。步骤如下：进入“设置”-->“应用”-->“Pathfinder”，打开“显示悬浮窗”选项。


LICENSE
==============
Licensed under the MIT(Massachusetts Institute of Technology)


相关资源
============
1. 灵云开放平台&灵云开发者社区：[http://www.hcicloud.com/](http://www.hcicloud.com/)。
2. 捷通华声灵云免费提供云端六大能力，包括语音识别ASR、语音合成TTS、手写识别HWR、图像识别OCR、语义理解NLU、机器翻译MT。
3. 登陆灵云开放平台及开发者社区，注册开发者账号，即可免费下载、使用六大能力SDK。


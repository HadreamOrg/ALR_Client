# 自学习AI机器人-Hadream-设备端

## 简介-Introduction
- 「自学习AI机器人-Hadream」是以能『自我学习』『自我意识』为目标的机器人项目。
- 本项目的运载设备应价格低廉，而不是过于昂贵的设备，只要求能够最低限度地『感知周围』即可。即听觉；视觉。
  - 因此最佳选择应是具备Raspbian系统的RaspberryPi-4。
- 为了能够使用不只一台设备进行测试，从而拥有更强的信息获取能力，同时为了降低运算成本，本机器人采用『统一大脑』。
  - 即Hadream的记忆与思考在一台拥有强大运算能力的计算机上进行。
  - 而实验设备则通过网络方式连接，将所感所知传递到『大脑』，『大脑』再根据这些信息作出学习和反应。
- 本项目为『设备端』代码
  - 要访问『云端』代码，请前往https://github.com/xiaoland/AutoLearningRobot_Hadream_Cloud

## 开发者-Developers
- Lan_zhijiang

## 基本信息-BasicInformation
- 语言
  - Python3
  - C++
- IDE
  - JetBrains-Pycharm社区版(我好穷)
- 库
  - opencv
  - tensorflow：tf.kears

## 文件架构-FileStructure
- auditory_system
  - device
  - process
- memory_system
  - personality_info_storage
  - memory_info_storage
  - device_info_storage
- speaking_system
  - client
  - cloud
- thinking_system
  - client
  - cloud
    - basic_nature_network
    - language_engine
    - logical_thinking
- vision_system
  - device
  - process

## 设计思想-Design

## 更新日志-UpdateLog
- 2020.5.30
  - 创建项目
  - 设计好文件目录上的基本架构
- 2020.5.31
  - 添加各个README.md
  - 设置好GithubPages和Webhook
  - 稍微更改文件架构
- 2020.6.21
  - 添加run.py
- 2020.6.26
  - 修改README.md
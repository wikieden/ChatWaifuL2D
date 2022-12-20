![cover](readme/cyberchat.png)

[中文](README.md "中文") [English](eng-README.md "English") [日本語](jp-README.md "日本語")

<p align="center">
	<img alt="GitHub" src="https://img.shields.io/github/license/cjyaddone/ChatWaifu?color=red">
	<img src="https://img.shields.io/badge/Python-3.7|8|9|10-green" alt="PYTHON" >
  	<a href="https://app.fossa.com/projects/git%2Bgithub.com%2Fcjyaddone%2FChatWaifu?ref=badge_small" alt="FOSSA Status"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2Fcjyaddone%2FChatWaifu.svg?type=small"/></a>
</p>

#


> ### 这是一个基于TTS+VITS的ChatGPT语音对话程序!

效果演示BiliBIli:[《青春猪头少年不会梦见赛博女友》](https://www.bilibili.com/video/BV1rv4y1Q7eT "BiliBili")

**当前支持功能：**
* [x] ChatGPT的对话聊天
* [x] 回答转语音
* [x] 多角色语音
* [x] 语音识别对话 (研发了一款真正人性化的智能语音Q宝
* [x] 对接Live2D的Web版本
* [x] 对接Marai机器人

# 目录
* [1.安装环境：](#1.)
	* 1.1 [使用cd命令进入项目文件夹](#cd)
	* 1.2 [创建Python虚拟环境:](#99)
	* 1.3 [进入创建好的虚拟环境:](#venv)
	* 1.4 [pip安装项目所需要的库文件:](#pip)
* [2.导入模型到根目录model文件夹（如果没有自行创建):](#.model)
	* 2.1 [双击导入model](#cd1)
* [3.运行（快和我的老婆们对话吧:](#22)
	* 3.1 [获取ChatGPT Token](#333)
	* 3.2 [2.开始和CyberWaifu聊天](#444)
* [4.鸣谢](#915)
## <span id="1.">1.安装环境：</span>
> **安装anaconda环境或Python>=3.7**
> 
> **本例使用的环境名称是：chatWaifu**

### <span id="cd">1.1 使用cd命令进入项目文件夹</span>
`cd 你的项目路径`


![](readme/5.png)
### <span id="99">1.2 创建Python虚拟环境:</span>

Conda:`conda create --name CyberWaifu python=3.10`
![](readme/1.png)
![](readme/2.png)
Python:`python -m venv chatWaifu`
![](readme/6.png)

### <span id="venv">1.3 进入创建好的虚拟环境:</span>
Conda:`conda activate chatWaifu`
![](readme/3.png)

Python:`.\chatWaifu\Scripts\activate.bat`
![](readme/7.png)

### <span id="pip">1.4 pip安装项目所需要的库文件:</span>
`pip install -r requirement.txt`
![](readme/4.png)

## <span id=".model">2.下载模型并解压到根目录model文件夹:</span>
Google Drive:https://drive.google.com/file/d/1tMCafhnUoL7FbevVQ44VQi-WznDjt23_/view?usp=sharing

阿里云盘: https://www.aliyundrive.com/s/9JEj1mp1ZRv 提取码: m2y3

### <span id="cd1">2.1移动到项目根目录下双击导入model</span>

## <span id="102">3.下载FFMPEG转换音频格式:</span>
### 使用浏览器打开：https://www.gyan.dev/ffmpeg/builds/ffmpeg-release-full.7z
### 解压后找到bin的路径，复制
![](readme/10.png)
### 使用Windows搜索栏搜索`高级设置`，找到并打开右下角的`环境变量`
![](readme/11.png)
### 在`系统变量`里面找到`Path`，双击更改，点击`新建`，把之前复制的路径粘贴进去即可
![](readme/12.png)

## <span id="101">4.下载Ren'Py
### 使用浏览器打开：https://www.renpy.org/
### 下载Ren'Py 8.0.3
### 解压后找到exe运行文件并打开，选择中文。打开设置，在一般下面找到项目目录，将其更改为ChatWaifuL2D的根目录
![](readme/8.png)
### 点击返回，点击项目旁边的刷新键，随后会出现一个名为ChatWaifuGameL2D项目，将其打开
![](readme/9.png)

## <span id="22">5.运行（快和老婆们对话吧:</span>

**当前支持语言：**
* [x] 中文版：`python ChatWaifuServer.py`
* [ ] 日语版
* [ ] 日语语音对话版（使用中文）
* [ ] 中文语音对话版（使用中文）
* [ ] 中文语音对话版（使用英文）
* [ ] 日语语音对话版（使用日文）

### <span id="333">5.1 获取ChatGPT Token</span>
#### 在浏览器登入https://chat.openai.com
#### 按F12进入开发控制台
#### 找到 应用程序 -> cookie -> __Secure-next-auth.session-token
#### 将值复制进入游戏终端并回车

### <span id="444">5.2 开始和CyberWaifu聊天！！！</span>

当控制台提示"You:"时开始说话，发送完整句子到游戏内进行对话。


## <span id="915">6.鸣谢：</span>
- [MoeGoe_GUI]https://github.com/CjangCjengh/MoeGoe_GUI
- [Pretrained models]https://github.com/CjangCjengh/TTSModels
- [PyChatGPT]https://github.com/terry3041/pyChatGPT

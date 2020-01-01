# -讯飞语音转文本Demo
## [讯飞平台官网](https://www.xfyun.cn/)  
## [API文档](https://www.xfyun.cn/doc/platform/xfyunreadme.html)
## [本项目语音转写文档](https://www.xfyun.cn/doc/asr/lfasr/Java-SDK.html#_2%E3%80%81sdk%E9%9B%86%E6%88%90%E6%8C%87%E5%8D%97)
  
## 使用步骤
### 1，首先在讯飞开放平台注册和申请用户并实名认证  
### 2，申请应用，获得密匙  
### 3，不同功能需求有不同密匙，当前密匙为语音转写密匙  
### 4，语音转写密匙需要在配置文件（config.properties）配置密匙：app_id、secret_key  
### 4，变量local_file为原始音频存放地址，需要自行更改  
### 5，转文本生成的txt文件和原始音频地址一致，暂时未做自定义选择目录功能，需要自行修改 
  
## 注：本Demo是在讯飞官方提供的案例Demo二次编译实现，实现在原始音频转文本的原始数据基础上，对音频转换的结果文本处理并保存本地文档。  
## 版权归讯飞官方所有

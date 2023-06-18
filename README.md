# | AutoAnimeMV:超轻量化快速部署看番遥遥领先！
<div align="center">
  <a href="https://github.com/Abcuders/AutoAnimeMV">
    <img src="./Image/logo.png">
  </a>

**全自动追番新时代！不动手才是硬道理！**


**简体中文 | [English](./Backups/1.20.1/README_en.md)**

*! En-README.md 由于我精力不够所以有太多落后未更新的地方,如果您感兴趣并且有时间的希望您能帮助一下我✊*

[![ GitHub 许可证](https://img.shields.io/github/license/Abcuders/AutoAnimeMv)](https://github.com/Abcuders/AutoCartoonMv/LICENSE) [![GitHub release](https://img.shields.io/github/v/release/Abcuders/AutoAnimeMv)](https://github.com/Abcuders/AutoAnimeMv/releases/) [![telegram](https://img.shields.io/badge/telegram-AutoAnimeMv-blue?style=flat&logo=telegram)](https://t.me/+3q1JuBrrPkJkOWJl)

***

 😊这是一个**番剧自动识别**`剧名剧集+自动重命名+自动整理的工具`,**具有部署方便,开箱即用的特点**,用来配合QBittorrent实现Rss订阅下载Emby全自动刮削一条龙到家式爽歪歪服务!

 </div>

* *2.0.0 版本我重写了1.0 的Code,优化了很多地方,但有些 1.0 的功能我还未更新到 2.0 版本,请您耐心等待*

> `工具更新较快,用法和功能都会更新,建议多来看看` 

> **🚀点击左上角打开目录，选择您要阅读的部分**


# 💡 功能说明
* **部署快速,使用方便的番剧视频/字幕重命名+整理工具**
>   
    动漫(分类)
    ├── 因为太怕痛就全点防御力了
    │   ├── Season01
    │   │   ├── S01E01.mp4
    │   │   ├── S01E02.mp4
    │   │   ├── S01E03.mp4
    │   │   └── ...
    │   └── Season02
    │       ├── S02E01.mp4
    │       ├── S02E02.mp4
    │       ├── S02E02.chi.srt
    │       └── ...
    |___ 無神世界的神明活動
    |    └── Season01  
    │        ├── S01E01.mp4
    │        ├── S01E01.chs.ass
    │        ├── S01E02.mp4
    │        └── ....
    |
    ......
    
* **一次配置,无感使用**
* **支持硬链接配置,保种必备**
* **支持番剧分类,让一切井井有条**
* **本地批处理和QB下载模式任君选择**
* **快速更新,享受更多新体验**

    ## 待更新的功能
    * BgmApi支持
    * TMDBApi支持
    * 本地番剧缓存
    * 完全番剧特典支持 

# 🚀 快速开始
* `AutoAnimeMv.py`是核心处理程序,它有俩种处理方式,模式的切换靠的是传参数量 [点我跳转到`AutoAnimeMv.py`点击右上角开始下载](https://github.com/Abcuders/AutoAnimeMv/blob/main/AutoAnimeMv.py)
    ## QB下载模式
    > 在此模式下`AutoAnimeMv.py`支持三到四个参数,`下载路径` `下载文件名` `下载文件数` `文件分类`(可选) 
    
    * 1.将`AutoAnimeMv.py`上传至`🔵QBittorrent`能访问的路径下
  
    * 2.在`🔵Qbittorrent`中创建`动漫`分类(非必须，当然不要分类也可以)

    * 3.修改qb配置: `下载`切换`Torrent 内容布局`为`不创建子文件夹`

    * 4.修改qb配置: `下载`勾选 `Torrent 完成时运行外部程序`, 下面填上(传入参数顺序不可更改且参数要用`""`包裹)
  
    ```
    python3 AutoAnimeMv.py放置路径 "下载路径" "下载文件名" "下载文件数" "文件分类(可选)" 
    ```
    上面三个参数可以由`🔵Qbittorrent`传入，即
    ```
    python3 AutoAnimeMv.py放置路径 "%D" "%N" "%C" "%L"(可选)
    ```
     > <img src="./Image/Example/two.jpg" width="400" height="300"> <img src="./Image/Example/three.jpg" width="400" height="300">
     * 4.取消做种，修改qb配置: 将`🔵QBitTorrent `的`做种限制`改成`当分享率达到0当做种时间达到0分钟然后暂停torrent`


    ## 批处理模式
    > 在此模式下`AutoAnimeMv.py`支持一到俩个参数,`需要整理的番剧所在路径` `文件分类`(可选) 
    
    * 传入参数顺序不可更改且参数要用`""`包裹
    ```
    python3 AutoAnimeMv.py "需要整理的番剧所在路径" "文件分类(可选)"
    ```

    ## 更新模式
    * 使用`updata`/`update`来更新`AutoAnimeMv.py`
    ```
    python3 AutoAnimeMv.py updata
    ```
# 详细的文档
* [点我到详细文档(其实就是1.0的文档,如上题所述1.0和2.0有部分不同,我会及早更新出2.0的详细的文档)](./Backups/1.20.1/README.md)

# 相关群组
* 交流/工作群: [Telegram](https://t.me/+3q1JuBrrPkJkOWJl)

# ⭐ 贡献者 ✨

**感谢这些有趣又很棒的人！！！**
> 如果您也想要为这个项目添砖加瓦,可以直接来[Issues](https://github.com/Abcuders/AutoAnimeMv/issues)提出您宝贵的建议或者@我问一下能做些什么

<a href="https://github.com/wzfdgh">
<img src="https://avatars.githubusercontent.com/u/93830081?s=96&v=4"  width="60px" height="60px"> 
</a>
<a href="https://github.com/Nanako718">
<img src="https://avatars.githubusercontent.com/u/60038246?s=96&v=4"  width="60px" height="60px">
</a>

# Star History
[![Star History Chart](https://api.star-history.com/svg?repos=Abcuders/AutoAnimeMv&type=Date)](https://star-history.com/#Abcuders/AutoAnimeMv)

# Ingress Report 简中搬运计划

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />本项目中 Ingress Report 中文翻译内容采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

## 工作流程

1. Ingress Report：每周四晚等待邮件和新视频

     - HTML 及自动生成字幕 -> Github
     - 低清视频 -> 度盘
     - 高清视频 -> 存档

2. QQ 群喊人，初译及时间轴 -> Github <-> 讨论润色

3. 最终版本压制

    1. 发布视频 -> [优酷]()，[腾讯]()
    2. 发布网页
    3. 微信推送
    4. 存档最终版本

4. 历史视频使用相同流程，无固定时间，分批发布

## 文件存放及规范

1. 所有文件按照月份归类存放，命名规则按照 **yyyyMM** 的格式
2. 来源于 Youtube 的英文原始字幕命名以 **.eng.srt** 结尾
3. 翻译及校对用的中文字幕命名以 **.chs.srt** 结尾
4. 最终用于压制和发布的中文字幕命名以 **.chs.ass** 结尾

### Github Fork-PR 流程

协作者既可直接向源项目推送提交，也可将项目 Fork 至自己名下，向源项目发起 Pull Request。

使用 Fork 时，需要在项目中添加源项目地址作为一个 upstream remote repo 用于和主项目保持同步（同步时应使用 git rebase）
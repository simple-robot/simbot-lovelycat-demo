# simbot Demo - 可爱猫

这是[simple-robot](https://github.com/ForteScarlet/simpler-robot) 框架使用[可爱猫组件](https://github.com/ForteScarlet/simpler-robot/tree/dev/component/component-lovelycat-httpapi) 对接[可爱猫](http://www.keaimao.com.cn/forum.php)的 [httpAPI插件](https://www.yuque.com/simpler-robot/simpler-robot-doc/dyb2s1) 的Demo项目。

## 需要做的
### fork/clone
fork或者clone此项目到你的本地，并使用IDE工具打开并构建它。

### 修改配置文件
打开文件 [simbot.yml](src/main/resources/simbot.yml) 并修改其中的 `simbot.core.bots` 项为你测试用的可爱猫wxid信息，例如：
```yaml
simbot:
  core:
    # 可爱猫中的bot的wxid 以及可爱猫http插件的接收地址
    bots: wxid_bxxxxxxxxxxx:http://localhost:88/httpAPI
```

### 保证安静
将你的bot放在一些测试用的群而不是一些大型群。

### 阅读
- [listener](src/main/java/simbot/example/listener) 包下为一些监听函数示例。阅读它们的注释，并可以试着修改它们。

### 运行
执行[SimbotExampleApplication](src/main/java/simbot/example/SimbotExampleApplication.java) 中的main方法。

### 协助
如果你有一个好的示例点子，你可以通过[github pr](https://github.com/simple-robot/simbot-lovelycat-demo/pulls) 来协助此demo项目的更新。


### 总体介绍

[matery2][1]是在[matery1][2]的基础和经验上开发的一款新的[ghost][3]博客主题,与前作一样的是，继承了`Material Design`和响应式的设计风格，但同时又更注重移动端的体验，遵循了移动优先的设计原则，更强调图片在博客和文章中的的响应式呈现。我的[个人博客][4]（闪烁之狐的博客）也切换成了这个主题。

### 主要特性

1. 响应式设计(移动端体验似Android app的体验)
2. `Material Design`设计
3. `瀑布流`式的博客文章列表(文章无特色图片时会有默认图片代替)
4. 自由切换主题风格(默认蓝色主题)
5. `hack`风格的代码高亮(高亮显示兼容性更强)

### 博客主题截图

桌面端博客首页截图:

![桌面端博客首页][5]

平板端博客首页截图:

![此处输入图片的描述][6]

手机端博客首页截图:

![此处输入图片的描述][7]

手机端博客导航截图:

![此处输入图片的描述][8]

手机端博文详情截图:

![此处输入图片的描述][9]

### 安装使用

当你看到本文的时候，应该已经有一个自己的ghost博客了，如果还没有的话，不妨去用ghost使用`Markdown`来写作，能够让人更加专注写作的内容本身，同时又能方便简单的排版显示。

当你安装好ghost博客之后，只需去本主题的github页[下载][10]下来，解压之后放在您博客的主题文件夹`content/themes/`里面，然后重启ghost博客，在博客后台`全局设置`页面选择本主题点击`保存`即可。

### 自定制修改

博客中的一些地方在博客后台管理界面里是无法设置的，但默认内容都是根据我自己的喜好设置的，您也可以修改成你自己喜欢的内容，改完之后重启Ghost即可。

#### 1、公告提醒栏

在博客的导航栏下有一`公告提醒栏`，，默认内容如下：

> 梦想面前做好自信的自己，自信可以改变未来。每一朵花都有开放的理由，你要始终坚信， 你就是你，一个独一无二的你，任何人都无法替代，不要因为别人的否定就轻易放弃，活在别人的世界里是一种悲哀，你要活出自己的本色。只要心在，梦就在，成功之前总是会遭受很多的磨砺，但是只要坚持做好手边的事， 自然会有意外不到的收获。

你可以在matery2主题中打开文件`index.hbs`，在31行中修改成你自己喜欢的文字即可。

#### 2、社交链接修改

社交链接由于区分了桌面端和移动端的显示方式，需要修改的有两处地方，一处是`partials/footer.hbs`文件中,另一处是在`partials/navigation.hbs`文件的最末尾。如果需要你也可以新增如微博、微信、`facebook`、`google+`等社交链接，修改成立需要的[Font Awesome][11]图标即可。

#### 3、底部版权信息修改

网页底部的版权信息如果你想改成自己的版权相关信息，也是在`partials/footer.hbs`文件夹中修改。

#### 4、修改默认主题颜色

网页的默认主题颜色是蓝色(`#3f51b5`)，如果你想修改成你喜欢的默认主题颜色，你可以去`assets/css/screen.css`中找到`.bf-color`和`.bf-text-color`两处修改其颜色值即可,你可以去这个[网站][12]寻找你喜欢的颜色。

### 祝你好运

祝你使用本主题写博客更舒心。本主题也必然有些不足之处，生命不息，折腾不止，如果有更好的设计和建议，我也会尽量抽出时间来完善，如果您发现了什么bug,可以给我发邮件给我。如果您觉得这个主题还不错的话，欢迎在github里star下以示支持，再次感谢。


  [1]: https://github.com/blinkfox/ghost-matery2
  [2]: https://github.com/blinkfox/ghost-matery
  [3]: https://ghost.org/
  [4]: http://blinkfox.com/
  [5]: http://static.blinkfox.com/matery2_1.jpg
  [6]: http://static.blinkfox.com/matery2_2.jpg
  [7]: http://static.blinkfox.com/matery2_3.jpg
  [8]: http://static.blinkfox.com/matery2_4.jpg
  [9]: http://static.blinkfox.com/matery2_5.jpg
  [10]: https://github.com/blinkfox/ghost-matery2
  [11]: http://fontawesome.io/
  [12]: http://www.materialui.co/flatuicolors

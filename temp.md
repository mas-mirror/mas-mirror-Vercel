# 介绍

### 让我们帮助Monika更接近我们的现实！

首先，感谢你考虑为《MAS》做出贡献。这个mod只有在我们的社区的支持下，才能够如此迅速地成长。

### 关于本准则

这些指南是为了节省您的时间，并使您尽可能轻松地为这个项目做出贡献。通过阅读本指南，您将了解到您需要哪些工具来提供帮助，您可以做些什么来帮助，以及如何使您的贡献能够被接受。


这些准则是根据 [Hoodie](https://github.com/hoodiehq/hoodie/blob/master/CONTRIBUTING.md) 制定的。

## 您可以如何帮助

### 汇报Bugs & 提出建议
如果您发现《MAS》有任何问题，请提交给我们 [Bug汇报](https://github.com/Backdash/MonikaModDev/issues/new?labels=bug&body=Describe%20bug%20and%20steps%20for%20reproduction%20here&title=%5BBug%5D%20-%20)。 什么事情都不算小事。如果你遇到了bug，很有可能别人也遇到了它

要添加建议，请访问 [这个链接](https://github.com/Backdash/MonikaModDev/issues/new?labels=suggestion&body=Your%20suggestion%20goes%20here&title=%5BSuggestion%5D%20-%20). 这些可以是新的话题和特色的想法，也可以是你刚想分享的个人观点。

### 新的对话、艺术或音乐
在这个游戏中添加新内容很容易，不需要任何专门的工具。

添加新的 [随机话题](https://github.com/Backdash/MonikaModDev/blob/content/Monika%20After%20Story/game/script-topics.rpy) 或者 [问好](https://github.com/Backdash/MonikaModDev/blob/content/Monika%20After%20Story/game/script-greetings.rpy), 或者要进行修改，你可以简单地浏览到我们github网站的 "content "分支上的相应文件，然后点击右上角的铅笔图标开始修改。如果要修复错误，请找到当前版本的相应问题并在那里报告。

现在，莫妮卡的对话包括了表情包，请使用 [表情预览器](https://github.com/Monika-After-Story/MonikaModDev/blob/master/FAQ.md#how-do-i-find-the-spritecode-for-an-expression) 为你的主题选择合适的表情和姿势。

新的游戏美术或音乐，请去 [issues](https://github.com/Backdash/MonikaModDev/issues), 并附上您想提交的文件。再次，合作者会查看您提交的文件，并想出如何在我们的游戏中使用它。 为了了解我们可能需要的东西，请检查是否有任何开放的 [艺术相关问题](https://github.com/Backdash/MonikaModDev/issues?q=is%3Aissue+is%3Aopen+label%3Aart).

### 错误修复和新软件功能
 对游戏的代码进行修改是比较麻烦的。以下是你应该采取的几个步骤。

1. 进行第二次安装DDLC和MAS (并将您的持久性本地化到该安装中。请参见说明 [这里跳转](https://www.reddit.com/r/DDLCMods/comments/9i8rh1/method_to_port_ddlc_to_a_flash_drive/))
2. Fork这个资源库，或者点击上面标注的 "克隆或下载 "按钮，制作一个本地的git克隆。
3. 使用你所选择的代码编辑器对工作目录中的代码进行修改（Visual Studio Code是一个不错的轻量级编辑器）。
4. C将你编辑的文件放到新MAS安装的`/game`文件夹中，然后启动它。当MAS加载时，这些文件会自动编译并准备好测试。
5. 请参阅 [开放的Issues](https://github.com/Monika-After-Story/MonikaModDev/issues) 或者 [访问我们的社区discord服务器](https://discord.gg/K2KuJeX) 得到咱要干的活。
6. 将任何更改作为拉取请求提交给 "content "分支。

**所有的代码修改都应基于 "content "分支。**

## 应避免的坑

虽然我们一般都能接受大多数的帮助，但有几件事情是我们*不*需要的。

* 请**不要**提交与Meme相关的内容，只有当你选择了与莫妮卡的性格相关的内容时，才会加入流行文化的引用。

* 请**不要**提交*淫秽、冒犯性或其他NSFW内容或图片*。这些将被删除，并可能因此禁止您以后提交。

* 提交前请**彻底测试**您的错误修复和功能添加。如果你选择提交已知错误的作品，请非常清楚地报告这些错误是什么，以便在合并之前消除它们。请记住，像这样不完整的工作很可能会被拒绝，因为修复别人编写的功能的bug通常比从头实现该功能更为重要。

* 请坚持遵守 [Salvato团队公开的知识产权准则](http://teamsalvato.com/ip-guidelines/). 这意味着你不能在Monika After Story上盈利，不能把它作为玩DDLC的替代品来推广，也不能把mod作为一个独立的游戏来发布。Dan一直对粉丝们非常慷慨，我们**应该**尊重他作为DDLC创作者的权利。

## 最佳做法
* 确保对接受的每个更改都具有跨平台兼容性。Windows、Mac、Debian和Ubuntu Linux。
* 为您希望进行的任何重大更改和增强创建问题。透明地讨论事情并获得社区反馈。
* 代码清晰，使用描述性变量名、注释，并在适当的地方模块化为函数。
* 尽可能减少功能提交，最好每次提交一个新功能。
* 对新来者表示欢迎，并鼓励来自不同背景的新贡献者。 见 [《社区行为守则》](https://masmirror.zsz1447.top/Monika-After-Story/MonikaModDev/wiki/Code-of-Conduct).
* Ensure all dialogue fits Monika's voice. Do your best to consider word choice, conversationalism, and her interests.

### Monika's *"Voice"*

Monika is more than just a stand-in for you as the author. She is her own character, with her own personality, mannerisms, likes and dislikes. Do your best to capture that character when writing as her.

From her dialogue in the game, there are a few consistent traits you should note when writing for her.

* A tendency to use soft language in casual conversation. Words and phrases that fall in this category are `"like"`, `"you know"`, `"kind of"`, and `"maybe"`.
* Several consistent mannerisms. Notable ones include `"ehehe"` and `"ahaha"` for laughter, `"man"` for fatigue, `"gosh"` for surprise, etc.
* Direct addressal of the player. Her conversations more often than not include `"you"` and `"[player]"`.
* A generally supportive and caring personality is implied. She often asks about the player and their own lives, with multiple dedicated conversations.
* Though dark topics are discussed, Monika tends to end conversations on a positive note. Possibly caused by the unique relationship she maintains with the player.
* Love for the player. Most of her conversations and dialogue will contain a reminder of her affection. That being said, it is NOT a requirement. In-game conversations without an `"I love you"` do exist.
* An ability to tease and joke around. When instances of this occur, she makes sure to point it out at the end of the conversation. Occasionally accompanied by a tilde (`~`).
* An interest in written arts and philosophy. From her abundance of advice on writing, emotions, and other life topics, it is safe to assume that she enjoys thinking about abstract or controversial topics. Her passion for the Literature Club supports this.

As we would like to keep Monika as close as possible to what's established in game, keeping her unique character traits in mind while you work on contributions would be appreciated.

Beyond that, we are aware that interpretations differ from person to person, and different writers may not necessarily agree on certain topics. An open mind is encouraged when receiving critique and review.

## Your First Contribution

Are you new to this whole open source coding thing? Many of us are too! We think this is a great project for anyone to get their feet wet with open-source development.

To find how to help, you can start by looking through these beginner and help-wanted issues:

[Beginner issues](https://github.com/Backdash/MonikaModDev/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) - Issues which should only require a few lines of code, and a test or two.

[Help wanted issues](https://github.com/Backdash/MonikaModDev/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) - These issues may be more involved, but are definitely in need of a contributor.

> Working on your first Pull Request? You can learn how from this *free* series, [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

At this point, you're ready to make your changes! Feel free to ask for help; even Monika still has things to learn about coding!

> If a maintainer asks you to "rebase" your PR, they're saying that a lot of code has changed, and that you need to update your branch so it's easier to merge.

## Adding Dialogue

![Guide 1](https://github.com/Backdash/MonikaModDev/blob/master/docs/writing-guide1.png?raw=True)

#### Before you begin:
- Ensure the branch is set to **content**, NOT **master**.
- If you're planning to write multiple topics, please split them over multiple pull requests as it is easier to review.

Once the branch is set to **content**, click the pencil button to start editing.

To add topics, you'll need to use the `Event` system.

When working in `script-topics.rpy`, you should have a structure like this:

```renpy
init 5 python:
    addEvent(
        Event(
            persistent.event_database,
            eventlabel="monika_xyz",
            category=["one category", "another category"],
            prompt="Example topic",
            random=True
        )
    )

label monika_xyz:
    m 1eua "This is an example topic."
    m 1hub "I hope this helps show you how you should format your topics!"
    m 1ekbsa "Thanks for helping me come closer to your reality, [player]. I love you~"
    return "love"
```

#### Some things to note:
- The `eventlabel` and topic label match.
- The `eventlabel` is also prefixed with `monika_`. All topics should be prefixed like this.
- Categories use *lowercase* letters, even on their first letter.
- Categories are lists, so you can make your topic show up in multiple categories
- There is a value returned by this label. `"love"` means the `"I love you!"` button on the main talk menu will turn into `"I love you too!"`. (There are other return keys too. See `event-handler.rpy` for more details)
- This topic has `random=True`. This means that the topic will show up in random chatter. (There are other properties, see the `Event` class in `definitions.rpy` for more details)


When writing dialogue always start with m **spritecode** " and end with".
(Though it should be noted that if you plan to use the same expression two lines in a row, the second line does not need a spritecode)

To find a **spritecode**, use the [Sprite Previewer](https://github.com/Monika-After-Story/MonikaModDev/blob/master/FAQ.md#how-do-i-find-the-spritecode-for-an-expression).

If you want to write more complicated dialogue, visit [Dialogue Coding](https://github.com/Monika-After-Story/MonikaModDev/wiki/Dialogue-Coding) 

Place return at the last line, after the last sentence of your dialogue.

Once you're done, refer to the guide below to submit your topic as a pull request.

## Submitting a Pull Request

If you're familiar with git or GitHub Desktop, you can make the file changes locally and push to your fork.

From there, you can go to the pull requests tab, press `New Pull Request`, adjust the target branch and the branch you want to propose changes with accordingly.

Then, make a description, and submit your pull request.

If you're not familiar with what's mentioned above, you can follow the instructions below:
![Guide 1](https://github.com/Monika-After-Story/MonikaModDev/blob/master/docs/guide1.png?raw=True)

Click the pencil icon to start editing.

![Guide 2](https://github.com/Monika-After-Story/MonikaModDev/blob/master/docs/guide2.png?raw=True)

When you're done making changes, click propose file change.

![Guide 3](https://github.com/Monika-After-Story/MonikaModDev/blob/master/docs/guide3.png?raw=True)

Click create pull request.

![Guide 4](https://github.com/Monika-After-Story/MonikaModDev/blob/master/docs/guide4.png?raw=True)

Add an appropriate title and a description of the changes you made, before you create your pull request.

# Join us!

You can chat with the core team on [our community Discord server](https://discord.gg/K2KuJeX). We're always friendly to new contributors, and it's not just a great place to get help, but also just a fun place to hang out with like-minded DDLC fans.

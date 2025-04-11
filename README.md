# Language-Model-Renamer
Language-Model-Renamer

Development Log:

**Phase 1:** 很早以前就在用各种工具爬免费音乐来听，但是爬出来的文件往往命名规则乱七八糟。如果能够快速的提取出歌曲名，那么按照FS的字母排序就非常容易找到想听的歌了

**Phase 2:** 试过Rule-based的renamer，但是往往效果不好，而且需要人工检查rules；

**Phase 3：** 也是本项目25-04-11提交的Notebook，通过HF的快速部署库来进行文件重命名，效率很高，准确率也相当不错。

TODO：

1. 可以改为OpenAI或DeepSeek的模型API，大模型准确率更高，如果能够联网Search则更加准确提取歌名；由于prompt限制，该操作API花不了几文钱。

2. 该Renamer当前prompt是仅为提取歌名使用；实际上可以通过更改prompt，来实现更复杂更高级的文件命名；

3. 25-04-11：可以通过多模态模型，来进行文件的Deep-Rename，用于大型Database Management，感兴趣可以联系作者hd31@rice.edu

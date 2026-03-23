现在我只要跟大模型说"帮我找下AI相关选题",它就会自动调用这个skill,几秒钟就能筛选出当下最热门的AI话题。

这是我花了一下午的时间创建的选题skill，它能辅助我做内容选题，效率真的提高了很多。

今天就手把手教大家怎么创建自己的skill。最后还会分享几个skill仓库，大家可以直接去里面找现成的用。

我想先强调一个非常重要但是很容易忽略的点，就是什么样的工作适合做成skill?。能做成skill的要具备这几个特性，一是这是不是你经常做的重复性工作，二它有没有一套比较固定的流程?，如果这两个特性都具备的话，就非常适合skill。

这是我们在做skill之前要想好的。

然后在Claude code 这类可以创建skill的agent 。我用的是谷歌的antigravity.

跟它说，我要创建一个XXX skill，主要是帮助我干什么的。我们先讨论，你先不要创建，你一个一个问题问我。

然后，它就会一个一个去问我问题。

这一步很关键。它会开始问你各种细节,比如你的具体需求是什么、输入输出是什么样的、有没有特殊要求。你就按照它的节奏,一个一个回答就行。

等它把情况了解得差不多了,你再把这个skill需要用到的知识、资料准备好,让它正式创建。

skill和提示词一样，不可能一次就完美。你得拿真实的case去测试,看看输出的内容是不是你想要的。如果不是,就继续调整,直到它能稳定输出你期望的结果。

有一个非常实用的技巧，就是你直接换一个模型，在问它，这个skill有没有可以改进的地方，然后体会帮你分析这个skill的优缺点，然后你在让它去修改。

对了,如果你不想自己从零开始做,可以去这三个skill仓库看看。里面有很多现成的skill,你可以直接拿来用:

**1.**[**http://skillsmp.com**](http://skillsmp.com)

**2.** [**https://github.com/anthropics/skills**](https://github.com/anthropics/skills)

**3.** [**https://github.com/ComposioHQ/awesome-claude-skills**](https://github.com/ComposioHQ/awesome-claude-skills)
# Demo10 - 自定义筛选或者搜索
- 本 demo 对作者源代码有一些改动：
-   1. 由于筛选时会对每个属性都进行一个check，且源代码中每个course的change属性都写有html字样，因此输入“h”时无筛选效果，故对预设数据进行了修改，并在 template 中加了一个条件判断的 r3
-   2. 源代码中，筛选会区分大小写，从使用体验来说，筛选一般不会做区别，因此添加了2处 toLowerCase()
- PS: 作者原有一篇自动筛选的 demo，以上大小写的改动也是从那里借鉴来的，但是该 demo 测试有问题，故一直没有正式提交，这里一并贴上链接 https://github.com/sunseekers/Vue/blob/91335c545319fefb2f170120616bf7075765dda4/dome2.html
# 交互可视化期末项目

- [Pythonanywhere链接](http://jx871614147.pythonanywhere.com/)：由于18同学没有将另一个页面部署，可以下载项目文档仓库到本地进行查看
- [项目文档仓库链接：](https://github.com/VickyCN/finalvisual)

## 项目背景
女性被家暴的新闻热点不断地冲击公众的视野，如最近如火如荼的宇芽家暴事件。因此，我展开了此次交互可视化项目的研究目的，旨在探讨：女性被施暴现象是否与接受教育水平和家庭类型相关，设立的相关法律是否能减少女性被暴力的几率。
## 数据来源
此次可视化数据交互的数据来源于联合国数据库，主要获取世界各国的男女性的受教育水平，各个国家存在的家庭类型，各国的反女性暴力的法规以及女性接受暴力的情况。
### 数据
- 世界各国存在的家庭类型
- 世界各国男性和女性接受的教育水平
- 世界各国针对女性被家暴设立的相关反家暴法的存在
- 在过去12个月，世界各地女性遭遇家暴

## 数据选择和清洗
#### 页面一：男性和女性的受教育水平和家庭情况

**教育水平**从联合国数据库下载的数据图表中，在性别选择处分为male、female 和 both sex 三种类型的性别选择，为了降低歧义和更好理解数据，我只选择了male 和 female 这样传统的性别选择。其次在教育水平上，联合国的数据细分了很多选择，我只选取First level、Second level 和 Third level。年龄划分上选取采取5个年龄为一个间隔。

**家庭类型**根据联合国数据库的数据下载，家庭类型划分为9种类型，我将其设置为自变量，将国家的家庭类型占比设置为因变量。

#### 页面二：反妇女暴力发和女性受暴力指数

**反妇女暴力法**根据联合国的数据统计，目前已有的针对反妇女暴力的法规，将法规分为家庭暴力法、性骚扰以及婚内强奸。将世界各个国家是否执行相关的法规制作为世界地图，可以更加直观看出。

**女性受暴力指数**根据数据统计，选取女性受暴力的values制作为世界地图。

## 数据描述
**页面一**

![页面一](https://images.gitee.com/uploads/images/2020/0103/233227_f03ed1cf_1648228.jpeg "页面一.JPG")

**页面二**

![页面二](https://images.gitee.com/uploads/images/2020/0103/233252_fcd103b0_1648228.jpeg "页面二.JPG")

我们看看页面一的“各国男性的受教育水平”和“各国女性的受教育水平”的堆叠图呈现的不同年龄段了解各国接受不同级别的教育情况。从堆叠图可以清楚看出，中国的的男性和女性在不同阶段的受教育水平都明显高于其他国家。个人推测可能中国的人口基数比较大的原因。但是在65岁之后明显看到德国男性和女性的受教育程度高于其他国家。随着年龄的增长，接受教育的水平逐渐降低。“各国男性的家庭类型”和“各国女性的家庭类型”的不同家庭类型呈现状况。我们可以明显看出加拿大在各个家庭类型同比其他国家要占据多数。页面二的反妇女暴力法规和女性受暴力指数的数据地图中，我们可以直观的看出一些北美洲、南美洲和澳洲一些较为发达的地区有设立相应的反妇女暴力的法律，而非洲部分地区的没有设立相应的反妇女暴力法规。在女性受暴力指数的世界地图中，看出澳大利亚的女性受暴力指数是最高的。

### 反思
在页面二中，我发现，好像有相关的法律法规建立，女性被暴力残害的指数会更高。根据目前从联合国数据库获得的数据，我发现这一结果。或许是数据的缺乏，或许是人类原始内心的反抗意识。这个项目后期可以寻求更多的数据探讨法律的规定是否能减少女性的家暴迫害。

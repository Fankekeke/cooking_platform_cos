### 基于SpringBoot + Vue的料理技巧分享平台

美食教学社区、厨艺进阶课堂、私房菜谱大全、美食家社交、小白学做菜、大厨经验分享、创意料理百科、厨房生活指南

### 管理员
公告管理，用户管理，消息管理，公告管理，敏感词管理，模块管理，消息回复，生鲜百科，留言板，首页管理

### 用户
用户登录注册，发布贴子，发布留言，发布贴子，贴子回复，贴子收藏，用户关注，消息通知

##### 内容生态与内容安全
###### 敏感词管理： 实时监测并拦截社区内的违规言论，确保料理心得分享环境健康且符合规范。

###### 模块/首页管理： 灵活配置热门菜谱与专题版块，优化首页布局，提升用户发现优质内容的效率。

###### 生鲜百科/管理： 打造权威食材与厨艺知识库，为用户提供科学的食材选购与预处理指导。

##### 社区交互与社交传播
###### 贴子发布/回复： 用户分享独家料理步骤或心得，支持多级评论互动，构建活跃的厨艺交流氛围。

###### 用户关注/粉丝： 建立美食达人关注体系，实时获取心仪博主的最新动态，增强社区的社交属性。

###### 留言板/发布： 提供开放的建议与反馈入口，方便用户与平台或博主进行非即时性的深度沟通。

##### 用户留存与个性化体验
###### 贴子收藏/整理： 用户一键保存实用料理技巧，建立个人专属食谱库，方便在厨房烹饪时随时回溯。

###### 消息通知/回复： 自动推送点赞、评论及关注消息，确保每一条互动反馈都能及时触达活跃用户。

###### 注册登录/管理： 维护全站用户基础档案，提供多端同步的个性化设置，保障平台用户数据的安全性。

##### 运营支撑与信息分发
###### 公告管理： 及时发布烹饪挑战赛、系统升级或社区规范，确保平台重要资讯的高效覆盖与透明。

###### 消息回复/管理： 管理员通过后台统一处理用户咨询，解决平台操作疑问，提升整体社区服务满意度。

#### 安装环境

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住

redis

Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]

WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok

#### 前台启动方式

安装所需文件 yarn install 
运行 yarn run dev

#### 后端启动方式

1.首先启动redis，进入redis目录终端。输入redis-server回车
2.导入sql文件，修改数据库与redis连接配置
3.idea中启动后端项目

#### 默认后台账户密码

[管理员]
admin
1234qwer

[用户]
fank
1234qwer



#### 项目截图
|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566191972.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566415786.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566599071.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566404248.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566477471.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566397169.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566460479.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566390351.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566452561.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566382377.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566435433.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566373826.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566425249.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733566363370.png) |
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/work/936e9baf53eb9a217af4f89c616dc19.png) |

#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.**黑奴价格**

> 项目部署调试不好包退！功能逻辑没讲明白包退！

#### 其它资源

[2025年-答辩顺利通过-客户评价🍜](https://berserker287.github.io/2025/06/18/2025%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)


#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)
****

<p><img align="center" src="https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/%E5%90%88%E4%BD%9C%E7%89%A9%E6%96%99%E6%A0%B7%E5%BC%8F%20(3).png" alt="fankekeke" /></p>

资源 | 网址
--- | ---
官方github | https://github.com/plantuml/plantuml
官方网站 | http://plantuml.com/zh/

##### mac 下，webstorm 中使用 PlantUML：
1. 安装 java
2. 安装 Graphviz：`brew install graphviz`
3. webstorm 安装 PlantUML 插件
4. 配置 GRAPHVIZ_DOT 环境变量：https://favoorr.github.io/2015/01/23/use-plantuml-install-graphviz/ ，显示环境变量信息：`echo $GRAPHVIZ_DOT`
5. 点击`@startuml`、`@enduml`之间的部分，会直接显示图

作用 | 命令
--- | ---
检测 Graphviz 是否安装 | 命令行`java -jar plantuml.jar -testdot`或文件里录入：`@startuml testdot @enduml`
产生图片 | `java -jar plantuml.jar -verbose sequenceDiagram.puml`

语法：

语法 | 作用 | 举例
--- | --- | ---
__ | 添加下划线 | `__下划线__`
标注文字则放在括号中 | |
`-[#green,dashed]->` | 给箭头添加颜色、形状 |
每个任务必须以分号结束 |  |

### 图的类型名称，中英文对照：

中文 | 英文
--- | ---
PlantUML是一个开源项目，支持快速绘制：|
时序图 | Sequence diagram
用例图 | Usecase diagram
类图 | Class diagram
活动图 | Activity diagram
组件图 | Component diagram
状态图 | State diagram
对象图 | Object diagram
部署图 | Deployment diagram 
定时图 | Timing diagram 
同时还支持以下非UML图: |
线框图形界面 | Wireframe graphical interface
架构图 | Archimate diagram
规范和描述语言 (SDL) | Specification and Description Language (SDL)
Ditaa 图 | Ditaa diagram
甘特图 | Gantt diagram 
MindMap diagram  | 
Work Breakdown Structure diagram  | 
以 AsciiMath 或 JLaTeXMath 符号的数学公式 | Mathematic with AsciiMath or JLaTeXMath notation

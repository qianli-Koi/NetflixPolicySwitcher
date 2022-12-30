# Netflix批量检测
## 新增功能
* 选择节点地区
* 开/关脚本通知

## 使用
1. 配置 Netflix 分流规则，并关联策略组（默认策略组为：Netflix，可在 BoxJs 中修改），支持策略组嵌套，但是只检测类型为 static 的子策略组
2. （可选）在 BoxJs 中订阅 [脚本集合](https://raw.githubusercontent.com/qianli-Koi/Scripts/master/Boxjs/boxjs.json)
3. 在 task gallery 中订阅 [脚本集合](https://raw.githubusercontent.com/qianli-Koi/Scripts/master/Boxjs/boxjs.json)
4. （可选）在 BoxJs 中配置分流策略组名称，以及其他参数
5. 必须先运行一次「解锁检测」脚本，后续该脚本会定时执行
6. 在 BoxJs 或 QuanX 中运行「策略切换」即可自动切换策略

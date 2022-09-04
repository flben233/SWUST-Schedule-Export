# SWUST-Schedule-Export
一个油猴脚本，可以将西南科技大学教务系统的课程表导出为JSON文件

## 内容列表

- [使用说明](#使用说明)
- [如何贡献](#如何贡献)
- [使用许可](#使用许可)

## 使用说明
脚本暂时没有上传Greasy Fork，导入脚本请直接打开本仓库中的js文件，全选并复制到剪贴板，在油猴的管理面板中点击 `+`，然后全选并粘贴

导入脚本到油猴，然后打开[教务系统](https://matrix.dean.swust.edu.cn/acadmicManager/index.cfm)
 
然后点击 `上课安排及学费明细` ，如果脚本成功启用，页面上应该会出现 `课表导出JSON` 按钮，点击即可导出为JSON文件

JSON文件示例如下(真实文件中不换行)：
```json
[{"day":3,
"name":"马克思主义基本原理",
"position":"东2333",
"sectionContinue":2,
"sectionStart":1,
"teacher":"小明",
"week":[1,2,3,4,5,6,7,8,9,10,11,12,13]}]
```
## 维护者

[@flben233](https://github.com/flben233)。

## 如何贡献

非常欢迎你的加入！[提一个 Issue](https://github.com/flben233/SWUST-Schedule-Export/issues/new) 或者提交一个 Pull Request。

## 使用许可

[MIT](LICENSE) © flben233


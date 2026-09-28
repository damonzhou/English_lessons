# 公开模板与私有学习记录分离

本仓库公开。课程协议、示例、空模板和播放器代码可以存仓库；儿童真实回答、声音、学校信息、已填进度和无公开分发权的教材文件不要提交。

## 第一次使用

在本地`system/`下新建`private/`，再复制空模板（需要时才创建子目录）：

| 公开模板 | 本地私有副本 |
| --- | --- |
| `02-Sessions/SESSION_TEMPLATE.md` | `private/02-Sessions/实际日期-材料ID.md` |
| `03-Listening-Cards/CARD_TEMPLATE.md` | `private/03-Listening-Cards/卡片ID.md` |
| `04-Reviews/QUEUE.md` | `private/04-Reviews/QUEUE.md` |
| `05-Weekly/REVIEW_TEMPLATE.md` | `private/05-Weekly/实际周次.md` |
| `01-Materials/MATERIAL_TEMPLATE.md` | `private/01-Materials/实际教材片段.md` |

真实音频放在`private/assets/`。公开模板保持空白，不覆盖填好后提交。

## 日常维护

家长先记录原始回答，再让AI按实际证据整理，核对后保存私有副本。提供给AI的内容只需当天材料、必要上次记录与到期卡，不需要整份儿童档案。

`.gitignore`忽略`private/`、本地Obsidian配置、音频和模板目录中的新增记录。但它不会保护已跟踪模板内填写的数据，也不是加密或权限控制，更无法阻止网页手动上传。提交前检查变更列表；不要强制添加私有文件。

本地备份与设备权限由家长自行管理。本次未为你建立自动同步、备份服务、账户连接或定时任务。

# Halou 客户更新发布仓

状态：配套发布，供现行客户端更新使用。源码在 [Halou](https://github.com/714167887-svg/Halou)；本仓保存客户更新包、签名清单和授权发布数据。

| 位置 | 用途 |
|---|---|
| 根 license.json 与 signed manifest | 稳定通道的授权/更新发布数据与可信产物清单 |
| candidates/ | 各版本候选包、灰度或发布流程留存 |
| release/ 及相关版本目录 | 客户安装、兼容版本与更新文件 |

现行插件由 Host / Contract / Payload 组成，并支持多套 AutoCAD SDK。具体版本以线上签名清单和授权发布数据为准。

维护通过移动盘工作区“更新Halou.cmd”及既有发布流程。旧包可能仍用于客户回退或版本钉选，未经使用关系核对不直接删除。仓库中的文件由发布管线生成，普通操作不手改清单、签名或 DLL。

[工作区及发布说明](https://github.com/714167887-svg/halou-wode-config)

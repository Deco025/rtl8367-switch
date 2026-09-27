# 3D 模型

下面 6 种器件的 3D 模型不在 KiCad 官方 3D 库里。它们来自立创商城，版权归原作者，所以**不随本仓库分发**。

只看原理图、PCB 或出生产文件时，不需要这些模型。想在 3D 查看器里看到完整外观，就按下表下载，**改成表中的文件名**，放进本目录（`3dmodels/`）。板上的封装已经指向这里，对齐参数也已设好。

| 文件名 | 器件 | 位号 | 立创料号 |
|---|---|---|---|
| `R-RJ45R08P-B000.step` | Ckmtw R-RJ45R08P-B000 网口 | J301、J401、J501、J601、J701 | C386756 |
| `C6384935_H5007NL.step` | Pulse H5007NL 网络变压器 | T301、T401、T501、T601、T701 | C6384935 |
| `C3096093_PJ-102AH.step` | PJ-102AH DC 插座 | J101 | C3096093 |
| `TS-1187A.step` | XKB TS-1187A 轻触开关 | SW101 | C318884 |
| `TPS54331DDA.step` | TI TPS54331DDA | U101 | C90761 |
| `1812L075_33DR.step` | Littelfuse 1812L075/33DR 自恢复保险丝 | F101 | C151170 |

- 下载方法：在立创商城打开对应料号页面，从 EasyEDA 的 3D 模型处导出 STEP。也可以用开源工具 [easyeda2kicad](https://github.com/uPesy/easyeda2kicad.py)，例如：`easyeda2kicad --3d --lcsc_id C386756`。
- 链接与许可说明见 [SOURCES.md](SOURCES.md)。

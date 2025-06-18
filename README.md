<div align="center">

<h1 align="center">OpenZxicEditor-For-Windows</h1>

**一个供 Windows便携使用 的Mifi~Studio ZXIC-RomKit开源分支**

</div>

---

#### ⚠️ No English documentation yet. If needed, please translate manually.

---

## 简介

一键解包和打包 zxic 烧录器固件的工具。

附带 MTD 分区的拆分和合并功能。

## 兼容性
此工具从OpenZxicEditor的老旧停止版本更新移植
已确认在以下Windows版本中可使用：

- windows10 及更高版本请直接使用
- 低于或等于 windows8.1 的版本不保证正常使用


## 使用方法

1. 您需要在电脑上安装MinGW并手动编译src中提供的lua546特殊版本，
完成后结合lua程序与lua脚本到ZXIC-RomKit中，并删除"bin/curl"以防固件上传。

2. 直接下载releases使用。

> [!NOTE]
> OpenZxicEditor-For-Windows依赖 ZXIC-RomKit ，但它并非完全开源的，因此属于 restricted 组件。<br>
> OpenZxicEditor-For-Windows已取得部分权利并默认附带在releases中。如果您反感此行为，请自行将其移除。


## 注意事项

1. 此程序尚不完善，可能存在一些问题，欢迎提出建议。
2. 开发时已留意了空格和中文路径的问题，但如果遇到迷惑 bug 可以尝试将文件放到简单路径下再试(如'MTDs')。
3. 如果某分区不需要修改，那么建议删除相应的解包文件夹，合并时将会自动使用原版。
4. 如需查看分区解包/打包时的详细信息(日志)，请创建文件`__lib__\--enable-log`。

## 使用须知

1. 禁止将此项目用于任何非法和不道德的行为，所造成的任何后果由使用者承担。<br/>
   且不建议将此项目用于商业用途，如遇纠纷及其他不良后果请贩卖者自行承担。
2. 如需二次开发，请遵守 AGPLv3 协议 (详见 开源许可.md)，并明确标注版权信息和出处。<br/>
   如果出于规避 AGPLv3 协议等目的需要仿制/重制本项目，请遵循白盒净室开发流程，并注明参考资料出处。

## 关于项目

1. 本项目的开发目的是研究 ZXIC 路由的固件格式，并希望为爱好者学习提供便利。
2. 目前仅确认支持ZX7520v3t芯片平台的固件，其他固件格式可能存在差异，请自行研究。
3. ufiStudio系列软件(含 OpenZxicEditor)现已完全由MiFi~Lab独立维护。即日起不再通过ufitech或uficlub发布。
4. ZXIC-RomKit的老旧闭源版本后续将移交分支给 企鹅君Punguin@punguin.cn 维护。
5. 欢迎各位用户和开发者提出建议，协助完善本项目。

# 小鹤双拼 for win
## 方案一： 手动修改注册表
- 右键开始 → 运行 ( `Win` + `R` )：`Regedit`（注册表编辑器）
- 定位计算机 `\HKEY_CURRENT_USER\Software\Microsoft\InputMethod\Settings\CHS`
- 右键 → `新建字符串值`
- 数值名称： `UserDefinedDoublePinyinScheme0`
- 数值数据： `小鹤双拼*2*^*iuvdjhcwfg^xmlnpbksqszxkrltvyovt`

## 方案二： 使用注册表文件
- 下载'xiaohe.reg' , 双击运行。

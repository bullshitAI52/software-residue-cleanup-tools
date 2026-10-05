# 专业软件与 CAD 残留清理工具

归档上传者提供的两个 Windows 可执行程序。这里只包含原始 EXE 文件，没有对应源码。

## 文件下载

| 文件 | 下载 |
| --- | --- |
| 专业软件残留清理工具.exe | [下载原始文件](https://github.com/bullshitAI52/software-residue-cleanup-tools/raw/refs/heads/main/bin/专业软件残留清理工具.exe) |
| CAD残留清理工具.exe | [下载原始文件](https://github.com/bullshitAI52/software-residue-cleanup-tools/raw/refs/heads/main/bin/CAD残留清理工具.exe) |

## 平台与验证范围

静态文件类型检查显示两者均为 Windows PE32 GUI 程序（Intel 80386）。macOS 不能直接运行，具体 Windows 版本兼容性尚未验证。

本次上传未执行程序，也未验证其清理范围、管理员权限需求或安全性。文件名称只是原始名称，不代表已经核实功能。使用前请自行确认来源并备份重要数据。

## 完整性校验

文件按原样保存，可用 [SHA256SUMS.txt](SHA256SUMS.txt) 核对下载后的完整性。哈希校验不等于安全检测。

Windows PowerShell 示例：

```powershell
Get-FileHash -Algorithm SHA256 '.\专业软件残留清理工具.exe'
Get-FileHash -Algorithm SHA256 '.\CAD残留清理工具.exe'
```

## 许可

提供的文件未附许可证，本仓库不擅自授予开源或再分发许可。相关权利归原权利人所有。

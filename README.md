# utaformatix-electron

把 https://sdercolin.github.io/utaformatix3 用nativefier和electron打包成本地应用

源代码：https://github.com/sdercolin/utaformatix3

打包代码（请先安装nodejs和nativefier，然后在cmd中运行）：

```
nativefier https://sdercolin.github.io/utaformatix3/ --file-download-options "{\"saveAs\":true}"
```

支持的输入文件：vsqx(3/4), vpr, ust, ccs, xml(MusicXML), musicxml, svp, s5p, dv, ppsf

支持的输出文件：vsqx(4), vpr, vsq, ust, ccs, xml(MusicXML), svp, s5p, dv

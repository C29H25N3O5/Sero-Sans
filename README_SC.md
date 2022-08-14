# Sero Sans

# 注意: 此字体目前正在开发过程中, 目前尚未完成。

Sero Sans是一款高度几何化的无衬线字体. 这款字体的灵感来源于DIN 1451､ Iosevka､ 和 JetBrains Mono的“胶囊状”字形. 名称“Sero”来源于血清素(5-羟色胺)的英文名称Serotonin, 一种在人脑中发现的神经递质, 被认为是愉悦感的贡献者.

## 特性

 ***(施工中)***

### ## 从源码构建

***(施工中, 目前不可用)***

你可以使用Glyphs(或其他字体编辑软件)来直接构建本字体, 或使用命令行工具Google Font Tools (`gftools`). 你需要Python 3.7或之后的Python来使用`gftools`.

1. 执行以下代码来安装 `gftools` :
   
   ```
   $ pip install gftools
   ```

2. 在命令行界面中移动到 `./.github/workflows/`;

3. 执行以下命令:
   
   ```
   gftools builder config.yaml
   ```

4. 在 `.github/fonts` 目录中找到构建好的字体文件.

## 对于非Glyphs用户

***(施工中, 目前不可用)***

强烈使用尽可能原始Glyphs文件来进行编辑和导出, 因为这些文件保留了原本的auto stroke以便于后期处理(尽管部分字符因为兼容性问题已被转换成纯轮廓).

但是如果出于某些原因不能使用Glyphs文件的话, 你也可以使用导出的UFO(Unified Font Object)文件, 但是请注意:

- 所有“用户友好”的字符形名称已被转换为产品名称(`uni####`).
  
  

## 许可

Sero Sans使用 [SIL开源字体许可, V1.1](https://github.com/26F-Studio/26F-Sans/blob/main/OFL.txt). 你可以免费使用､ 修改和重新分发编译的字体和源文件, 而无需提及作者本人 (但你也可以这么做).

本仓库其他部分代码使用[MIT 协议](https://github.com/26F-Studio/26F-Sans/blob/main/MIT.txt).

# 作者

- 字体设计和测试: C₂₉H₂₅N₃O₅ 

# Sero Sans

# NOTE: THIS TYPEFACE IS CURRENTLY UNDER CONSTRUCTION AND HAS NOT BEEN FINISHED AT THIS MOMENT.

[Click here to view the Simplified Chinese Version 点击这里来阅读简中版本](README_SC.md)

Sero Sans is a highly geometric sans serif typeface. It was inspired by the capsule-shaped glyphs found in DIN 1451, Iosevka, and JetBrains Mono. The name “Sero” comes from serotonin, a neurotransmitter found in human brains and is thought to be a contributor to the pleasure sense.

## Features

***(Under Construction)***

## Build from Source

***(Under Construction, not available at this time)***

You can either build the fonts using the Glyphs app (or other font editing programs) directly, or you can choose to build them in the command line using the Google Font Tools (`gftools`). You have to install Python 3.7 or later to use `gftools`.

1. Install `gftools` by executing the following command:
   
   ```
   $ pip install gftools
   ```

2. Navigate to `./.github/workflows/` in the command line.

3. Execute the following command:
   
   ```
   gftools builder config.yaml
   ```

4. Find the compiled fonts in the `.github/fonts` folder.

### Notes for non-Glyphs users

***(Under Construction, not available at this time)***

It is strongly recommended to use original Glyphs files whenever possible as it preserves the original auto strokes for easier editing (though some glyphs are decomposed in order to avoid compatibility issues). 

But if that is not possible for you, you can also use the exported UFO (unified font object) files as an alternative choice. However:

- 

- Since UFO does not support multiple masters, you need to interpolate using specific programs in order to get multiple weights and variable fonts by combining the provided masters in UFO.

- All the user-friendly glyph names are converted to production names (`uni####`).

## License

Sero Sans is under a [SIL Open Font License, Version 1.1](https://github.com/26F-Studio/26F-Sans/blob/main/OFL.txt). You can use, modify, and redistribute the compiled fonts and the source files free of charge and you do not need to attribute to 26F Studio (But we would appreciate that if you do so).

The other part of the source code in this repository is under a [MIT License](https://github.com/26F-Studio/26F-Sans/blob/main/MIT.txt). 

## Credits

* Type Design and Testing — C₂₉H₂₅N₃O₅

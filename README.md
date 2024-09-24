# InfoCo-beamer-template

Hi👋 Here are some beamer templates which are secondary creations of [SINTEF Presentation](https://www.overleaf.com/latex/templates/sintef-presentation/jhbhdffczpnx) template and [college-beamer](https://github.com/liu-qilong/college-beamer). Thanks [Federico Zenith](federico.zenith@sintef.no) for creating such well-designed works. To use it in my and my friends' schools/institutes, I rewrote and added some icons and features to adapt to specific surroundings✨.

This is the template modified and used for XJTLU InfoCo.

For the full contribution lists, please go to [college-beamer](https://github.com/liu-qilong/college-beamer).

> Noted that if you'd like to include Chinese text, please use XeLaTeX for typesetting.

## Usage

```
\usepackage[en]{infocoBeamer}
```

### Switch language

To switch the language, just change the language option in the `infocoBeamer` package. For example, to switch to the Chinese language, add `zh` to the package:

```
\usepackage[zh]{infocoBeamer}
```

> When select `zh`, please add the `xeCJK`package to the preamble and use XeLaTeX as the typesetting engine.

```
\usepackage{xeCJK}
```

## Gallery Showcase
- Cover page
![cover](https://github.com/Zerlight/InfoCo-beamer-template/blob/main/gallery/cover.png?raw=true)
- Table of Contents

  At the beginning of each section, the table of contents will be shown with the current chapter highlighted.
![toc](https://github.com/Zerlight/InfoCo-beamer-template/blob/main/gallery/table%20of%20contents.png?raw=true)
- Sub-section page
![math](https://github.com/Zerlight/InfoCo-beamer-template/blob/main/gallery/math.png?raw=true)
- Code block
![code](https://github.com/Zerlight/InfoCo-beamer-template/blob/main/gallery/code.png?raw=true)
- End page
![end](https://github.com/Zerlight/InfoCo-beamer-template/blob/main/gallery/end.png?raw=true)

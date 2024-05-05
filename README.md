# FoundryVTT - DrawingTokenizer
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/FOCCms/DrawingTokenizer?style=for-the-badge) 
![GitHub Releases](https://img.shields.io/github/downloads/FOCCms/DrawingTokenizer/latest/total?style=for-the-badge) 
![GitHub All Releases](https://img.shields.io/github/downloads/FOCCms/DrawingTokenizer/total?style=for-the-badge&label=Downloads+total)  

**[Compatibility]**: *FoundryVTT* 11+  
**[Systems]**: *any*  
**[Languages]**: *English*  

Ever wanted to use your drawings for your tokens and actors? This module enables you to convert your drawings into images and use those for your tokens, actors etc.

## V10 original
It is modification of this module (https://github.com/KayelGee/DrawingTokenizer). I just added v11 support.

## Installation

1. DrawingTokenizer using manifest URL: https://raw.githubusercontent.com/FOCCms/DrawingTokenizer/master/module.json
2. While loaded in World, enable **_DrawingTokenizer_** module.

## Usage

Select the drawings tool. Select your drawings you wish to convert, then click the convert to image tool. Type in a name and you'll find you image in "yourworld/DrawingTokenizerData/yourimage.png".
WebP export is currently only supported by Chrome, but this is dynamically checked, so if your browser adds support then this will be automatically enabled.

![](DrawingTokenizer.gif)
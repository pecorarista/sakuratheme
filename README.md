Sakura theme
============

これは主に日本語を対象とした beamer のテンプレートです．  
[mtheme](https://github.com/matze/mtheme) を元に作成しています．

![スクリーンショット](screenshot-gloss.png)

## Requirements

+ [TeX Live 2016 or later](https://www.tug.org/texlive/)
+ [jecon.bst](https://github.com/ShiroTakeda/jecon-bst)

## Example

使用例のソースコードは `demo.tex` です．出力結果は `demo.pdf` になります．

## Typesetting

`latexmk demo.tex` で PDF が作成されます．
ファイルの変更が起きるごとにタイプセットしたい場合は `latexmk -pvc demo.tex` としてください．

## License

[Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/) 

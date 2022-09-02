
<h1 align="center">Optimized Stable Diffusion<br>japanese version</h1>

低VRAM版PCに対応した<a href="https://github.com/basujindal/stable-diffusion">Optimized Stable Diffusion</a>のスクリプトを少し改変したものです

<br>
▼特徴<br>
・Google翻訳のテキストボックスを導入<br>
・画面レイアウトをカスタマイズ<br>
<br>
※optimizedSDフォルダ以外は、<a href="https://github.com/basujindal/stable-diffusion">basujindal/stable-diffusion</a>を使用してください

## 前提
- Python 3.10.x
- basujindal版のstable-diffusionが導入済み
- 以下のライブラリーをインストールする<br>
  pip install 'googletrans==4.0.0rc1'

## 導入
1. optimizedSDフォルダーを上書き<br>
　basujindal版のstable-diffusionにある、optimizedSDを上書きます<br>

2. 実行する<br>
  stable-diffusionフォルダで以下のコマンドを実行する<br>
　python .\optimizedSD\txt2img_gradio_jp.py<br>

## Author
@virtuarian


## 変更履歴

- v0.1: 日本語変換のボックスを追加.

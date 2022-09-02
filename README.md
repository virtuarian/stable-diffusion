# Update: v0.1

[Added support for inpainting](#inpainting)

<h1 align="center">Optimized Stable Diffusion<br>japanese version</h1>

<a href="https://github.com/basujindal/stable-diffusion">低VRAM版のStable Diffusionのスクリプトを少し改変したものです<a>

<br>
▼特徴<br>
・Google翻訳のテキストボックスを導入<br>
・レイアウトを変更<br>
<br>
optimizedSDフォルダ以外は、<a href="https://github.com/basujindal/stable-diffusion">basujindal/stable-diffusion</a>を使用してください


<h1 align="center">Installation</h1>

# 前提
- Python 3.10.x
- basujindal版のstable-diffusionが導入済み
- 以下のライブラリーをインストールする
  pip install 'googletrans==4.0.0rc1'

1. optimizedSDフォルダーを上書き
　basujindal版のstable-diffusionにある、optimizedSDを上書きます

2. 実行する
  stable-diffusionフォルダで以下のコマンドを実行する
　python .\optimizedSD\txt2img_gradio_jp.py

## Changelog

- v0.1: 日本語変換のボックスを追加.

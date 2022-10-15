# vscode-dev-container-nvidia-cuda-sample

VSCode Dev Container で [rinna/japanese-gpt-1b](https://huggingface.co/rinna/japanese-gpt-1b) のサンプルコードを動かす環境を構築するサンプルです。

## 前提条件

- VSCode Dev Container を使用できる環境
- CUDA インストール済み

## CUDA と cuDNN のバージョンについて

[Development Container Features](https://github.com/devcontainers/features) で CUDA と cuDNN のインストールを行うため、 `.devcontainer/devcontainer.json` の `features` フィールド内にある項目からバージョン変更を行えます。  
[NVIDIA のリポジトリ](https://developer.download.nvidia.com/compute/cuda/repos/ubuntu2004/x86_64/) に存在する組み合わせを確認しながらバージョンを設定すると失敗を避けることができます。

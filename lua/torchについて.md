# 開発者

	
Ronan Collobert (Facebook), Clement Farabet (Twitter), Koray Kavukcuoglu (Google DeepMind), Soumith Chintala (Facebook)

# 説明

http://torch.ch/

LUAJITの科学的な計算フレームワーク

>Torchは、GPUを最優先にする機械学習アルゴリズムを幅広くサポートする科学計算フレームワークです。簡単で高速なスクリプト言語、LuaJIT、および基礎となるC / CUDA実装のおかげで、使いやすく効率的です。
コア機能の要約： 強力なN次元配列 インデックス作成、スライス、転置などの多くのルーチン… LuaJITを介したCへの素晴らしいインターフェース 線形代数ルーチン ニューラルネットワーク、およびエネルギーベースのモデル 数値最適化ルーチン 高速で効率的なGPUサポート iOSおよびAndroidバックエンドへのポートを備えた埋め込み可能

Start with our Getting Started guide to download and try Torch yourself.   

http://torch.ch/docs/getting-started.html


# pytorch

https://pytorch.org/

>ツールとライブラリ ツールとライブラリの豊富なエコシステムは、PyTorchを拡張し、コンピュータービジョン、NLPなどの開発をサポートします。
開発をサポートするために、ライブラリ、ツールなどの豊富なエコシステムを探索します。

# どっちがいいのか?

https://stackoverflow.com/questions/44371560/what-is-the-relationship-between-pytorch-and-torch

>NumpyのようなTensorライブラリ。Numpyとは異なり、強力なGPUサポートを備えています。 LuaはTorchのラッパーです（はい！Luaを十分に理解する必要があります）。そのためにはLuaRocksパッケージマネージャーが必要です。

>PyTorchとTorchの両方がTHNNを使用します。 TorchはTHNNライブラリにluaラッパーを提供し、Pytorchは同じためにPythonラッパーを提供します。 

>詳細については、こちらのディスカッションセッションをご覧ください。https://discuss.pytorch.org/t/torch-autograd-vs-pytorch-autograd/1671

##### THNN

https://github.com/torch/nn/tree/master/lib/THNN

>THNNは、nnのニューラルネットワークモジュールのC実装を収集するライブラリです。


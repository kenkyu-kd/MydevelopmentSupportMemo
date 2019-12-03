# サイト

https://opencv.org/

# introduction

https://docs.opencv.org/4.1.2/d1/dfb/intro.html

>このドキュメントでは、いわゆるOpenCV 2.x APIについて説明します。これは、CベースのOpenCV 1.x APIとは対照的に、本質的にはC ++ APIです

- Core functionality (core)
  - 密な多次元配列Matおよび他のすべてのモジュールで使用される基本関数を含む、基本的なデータ構造を定義するコンパクトなモジュール
- Image Processing (imgproc) 
  - 線形および非線形画像フィルタリング、幾何学的画像変換（サイズ変更、アフィンおよび遠近法のワーピング、一般的なテーブルベースの再マッピング）、色空間変換、ヒストグラムなどを含む画像処理モジュール。
- Video Analysis (video) 
  - モーション推定、バックグラウンド減算、オブジェクト追跡アルゴリズムを含むビデオ分析モジュール。
- Camera Calibration and 3D Reconstruction (calib3d)
  - 基本的なマルチビュージオメトリアルゴリズム、単一およびステレオカメラキャリブレーション、オブジェクトポーズ推定、ステレオ対応アルゴリズム、および3D再構成の要素
- 2D Features Framework (features2d) 
  - 優れた機能検出器、記述子、および記述子マッチャー。
- Object Detection (objdetect)
  - 事前定義されたクラス（たとえば、顔、目、マグカップ、人、車など）のオブジェクトとインスタンスの検出
- High-level GUI (highgui)
  - シンプルなUI機能への使いやすいインターフェイス。
- Video I/O (videoio)
  - ビデオキャプチャおよびビデオコーデックへの使いやすいインターフェイス。
- FLANNやGoogleテストラッパー、Pythonバインディングなど、その他のヘルパーモジュール。

# 各モジュールの機能について説明

cv Namespace

>すべてのOpenCVクラスと関数は、cv名前空間に配置されます。したがって、コードからこの機能にアクセスするには、cv ::指定子を使用するか、名前空間cvを使用します。

```
#include "opencv2/core.hpp"
...
cv::Mat H = cv::findHomography(points1, points2, cv::RANSAC, 5);
...
```

or

```
#include "opencv2/core.hpp"
using namespace cv;
...
Mat H = findHomography(points1, points2, RANSAC, 5 );
...
```

他にもチュートリアルあり

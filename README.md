<!--
  使い方:
  1. ユーザー名と完全に同じ名前のリポジトリ「taru104」を新規作成（Public）
  2. このファイルを README.md としてそのリポジトリに置く
  3. 下の TODO（QiitaのURL・視線推定リポジトリ名の確認）だけ直す
-->

# こんにちは、taru104 です 👋

コンピュータビジョン（CV）を中心に学んでいるエンジニア志望です。
大学院では量子コンピューティングも研究していて、今後そのコードも公開していく予定です。
学んだことを小さなプロダクトの形にして積み上げています。

## 🛠 技術スタック

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/-MediaPipe-0097A7?logo=google&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TensorFlow.js](https://img.shields.io/badge/-TensorFlow.js-FF6F00?logo=tensorflow&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML/CSS-E34F26?logo=html5&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)

## 🚀 主なプロジェクト

### 👁 リアルタイム視線推定システム　— [my_gaze_project](https://github.com/taru104/my_gaze_project)
<!-- TODO: 公開リポジトリ名が my_gaze_project でなければURLを修正してください -->
Webカメラ1台で、画面上のどこを見ているか（注視点）をリアルタイムに推定します。MediaPipe で顔・虹彩ランドマークを検出し、**距離不変の特徴量**を設計、アフィン回帰でキャリブレーションし、One Euro フィルタで平滑化する**軽量・非DNN**の構成です。GazeCapture データセットで定量評価し、**EyeTrax ベースライン（median 約16cm）を上回る median 約7.8cm** を達成しました。

### 📸 リアルタイム物体検出 Web アプリ　— [Real-time-Object-Detection-Web-App](https://github.com/taru104/Real-time-Object-Detection-Web-App)
TensorFlow.js + COCO-SSD で、ブラウザ完結のリアルタイム物体検出を行います。**推論はすべてクライアントサイド**で実行され、映像はサーバーに送られません。ビルド不要の単一 HTML 構成です。

### 💰 おこづかい管理アプリ　— [allowance-app](https://github.com/taru104/allowance-app)
Vanilla JS 製の PWA。収支の記録と残高管理ができ、オフライン動作・ホーム画面へのインストールに対応しています。

### 🤏 あんちをツンしよう　— [my-image-pwa](https://github.com/taru104/my-image-pwa)
息抜き用のゆるい PWA。技術の素振りも兼ねた遊び心枠です。

## 🌐 Currently working on

I'm focusing on **computer vision**. Right now I'm building a real-time **gaze estimation** system that runs on a single webcam (MediaPipe + affine calibration + One Euro filter), benchmarked on the GazeCapture dataset, and a browser-based **real-time object detector** with TensorFlow.js. Alongside this, I'm studying **quantum computing** in graduate school and plan to share that code soon.

## 📝 Links

- Qiita: <!-- TODO: QiitaのURLを貼ってください（記事が増えてきたら見せ場になります） -->

## 📊 GitHub Stats

![taru104's GitHub stats](https://github-readme-stats.vercel.app/api?username=taru104&show_icons=true&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=taru104&layout=compact&hide_border=true)

<!--
  遊び心をもう一段足したい場合（任意）:
  コントリビューショングラフを蛇が食べるアニメは、別途 GitHub Actions の設定が必要です。
  欲しくなったら声をかけてください。手順を案内します。
-->

---

<sub>学んだことを小さく形にして積み上げています。気軽にのぞいてください。</sub>

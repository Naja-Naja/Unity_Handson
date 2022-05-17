# chapter9 BGMを付けよう/効果音を付けよう
## BGMを付ける
- [よさげなBGM](https://dova-s.jp/bgm/play4551.html)をダウンロードしてきて、Unityのプロジェクトウィンドウにドラッグアンドドロップする
- ヒエラルキーに空のゲームオブジェクトを作成し、AudioSourceコンポーネントを追加する
- AudioSourceコンポーネントのAudioClipにプロジェクトウィンドウのBGMをドラッグアンドドロップする
- ゲーム開始時に再生・ループにチェックをいれて音量を調整する（デフォルトだとかなり大きい）
- 再生してみる

## 効果音を付ける
- [よさげな効果音](https://soundeffect-lab.info/sound/anime/mp3/papa1.mp3)をダウンロードしてきて、Unityのプロジェクトウィンドウにドラッグアンドドロップする
- PlayerにAudioSourceを追加してAudioClipに効果音をドラッグアンドドロップする
- ゲーム開始時に再生・ループのチェックを外して音量を調整する
- PlayerのScriptMachineに以下のように追記  
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/flow12.png)
- 再生してみる

### 発展
- 他の行動にも効果音を付けてみる
- StartボタンでBGMを切り替えてみる

[次:chapter10 ビルドしてみる](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/chapter10.md)  
[前:chapter8 エフェクトを作ろう](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/chapter8.md)   
[目次](https://github.com/Naja-Naja/Unity_Handson) 

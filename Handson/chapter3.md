# chapter3 プレイヤーを動かしてみる
## VisualScriptingの準備  
- 先ほど作ったPlayerオブジェクトにScriptMachineのコンポーネントを加える
- ScriptMachineのNewボタンを押して新しいGraphを作成する(名前はplayerとか適当でOK)
- Edit Graphを選択すると新しいウィンドウが立ち上がる

## 移動してみる
- 以下の図のように組んでみる
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/flow1.png)
- 再生して横入力（A/D　←/→）してみる
- rigidbodyの質量を調整してみる(0.2とか)
- 再生して横入力してみる
- 横入力の機構を複製して縦入力も作ってみる(Addforceはzに入力)  
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/flow2.png)
- 移動はできたけどなんかすごく慣性のかかるものができあがる

## 移動を改善してみる
- 以下の図のように組んでみる
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/flow3.png)
- 再生して十字入力をしてみる
- 操作感が変わった

## カメラを追従させてみる
- maincameraをPlayerの子オブジェクトにしてみる
- 再生してみる
- 改善前の動きにしてみる
- 再生してみる
- maincameraをプレイヤーの子オブジェクトから外す
- maincameraにChinemachineBrainを追加する
- ヒエラルキーの空白を右クリックし、Chinemachine>VirualCameraを追加してみる
- 以下のように設定  
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/chinemachine.png)  


### 発展
- マウスでのエイムを実装してみる


[次:chapter4 ジャンプさせてみる](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/chapter4.md)  
[前:chapter2 オブジェクトを置いてコンポーネントを付けてみる](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/chapter2.md)   
[目次](https://github.com/Naja-Naja/Unity_Handson) 

# VisualScriptingの準備  
- 先ほど作ったPlayerオブジェクトにScriptMachineのコンポーネントを加える
- ScriptMachineのNewボタンを押して新しいGraphを作成する(名前はplayerとか適当でOK)
- Edit Graphを選択すると新しいウィンドウが立ち上がる

# 移動してみる
- 以下の図のように組んでみる
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/flow1.png)
- 再生して横入力（A/D　←/→）してみる
- rigidbodyの質量を調整してみる(0.2とか)
- 再生して横入力してみる
- 縦入力も作ってみる  
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/flow2.png)
- 移動はできたけどなんかすごく慣性のかかるものができあがる

# 移動を改善してみる
- 以下の図のように組んでみる
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/flow3.png)
- 再生して十字入力をしてみる
- 操作感が変わった

# カメラを追従させてみる
- maincameraをPlayerの子オブジェクトにしてみる
- 再生してみる
- 改善前の動きにしてみる
- 再生してみる
- maincameraにChinemachineBrainを追加する
- インスペクターを右クリックし、Chinemachine>VirualCameraを追加してみる
- 以下のように設定
![flow1](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/cinemachine.png)
- 応用：ほかにもマウスでのエイムや定点カメラなども実装できる

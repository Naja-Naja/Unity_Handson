# 各オブジェクトにマテリアルを設定する
- プロジェクトウィンドウの空きスペースを右クリックして作成(Create)>マテリアル(Material)を選択
- 名前をPlayerにする
- アルベドを好みの色にする
- ヒエラルキー上のplayerを選択し、インスペクターウィンドウのMeshRenderer>Materials>要素(elements)0にドラッグアンドドロップでマテリアルを設定
- プレイヤーの色が変わる
- 床やゴールの色も変えてみる

# Skyboxを設定する
- window>Rendering>Lightingからライティングウィンドウを開き環境のスカイボックスマテリアルを「プロジェクトの作成」でダウンロードしたスカイボックスに変更　　

  
![window](https://github.com/Naja-Naja/Unity_Handson/blob/main/Handson/lightingwindow.png)  


### 発展
- さらに余裕のある人はPostprocessingでBloomをつけてみる

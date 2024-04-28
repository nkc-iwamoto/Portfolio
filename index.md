# Portfolio

## 自己紹介
氏名(カナ)　　岩本彩杜(イワモトアヤト)  
名古屋工学院専門学校在学 25卒業予定  
生年月日　　 2003/2/13   
ゲーム歴　　　12年  

C#とUnityを中心に学んでいます。  
ギミック制作が好きです。

## 学習した技術  

授業で習った　 ☆☆☆☆☆　　自信がある  

| 技術     | 理解度 | 学習歴(年) |
|----------|--------|-----------|
| C#       | ★★★☆☆  | 3年        |
| Unity    | ★★★☆☆  | 3年        |
| C++      | ★★☆☆☆  | 2年        |
| HTML/CSS | ★☆☆☆☆  | 1年        |


## これまでに作った作品
## 曲げて進め！レーザーダンジョン
<iframe width="560" height="315" src="https://www.youtube.com/embed/vAu2sqNFRJk?si=jxL4nvV1QPAkAsC1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### ゲーム内容
スイッチを押してレーザーを曲げギミックを解いていくゲームです。

### 背景　　
日本ゲーム大賞2023 アマチュア部門とゲームクリエイター甲子園2023に向けて制作したゲームです。

### 制作環境

| 環境         | 内容                   |
|--------------|-----------------------|
| 人数         | 6人(プログラマー6人)   |
| 使用ツール/言語 | UnityC#             |
| 期間         | 500時間(2か月)　　　　 |
| 担当箇所     | レーザー周りのギミック  |
|リファクタリング|不定期更新|  

### こだわった所
- レーザーを曲げる処理や分岐させる処理、レーザーを当たった時のスイッチの処理を発射元のUpdateが全て呼び出している所

毎フレームごとにギミックが今レーザーに当たっているか調べることをしたくなかったためです。  
レーザーを当てた側はRaycastで当てた物がわかるが、当てられた側はレーザーが今当たっている/いないの判定を取ることが難しいと感じました。  
また判定を取れたとしてもUpdate内で当たっている/いない処理を行うより、当てられた/離れた処理を宣言したIHitableのようなインターフェースをギミックに継承させ,   
それをレーザー側から呼び出せば、判定を取らなくても良くなり、Updateに不必要な処理を書かなくて良くなるためです。  


#### 受賞
ゲームクリエイター甲子園2023　B.B.スタジオ賞　　
第12回全国専門学校ゲームコンペティション プレイアブル部門　ファイナリスト　　

## UniVerSus
<iframe width="560" height="315" src="https://www.youtube.com/embed/qqtdCZ1KiGo?si=CnDBOZUkjC-QWpYU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### ゲーム内容　　
お邪魔アイテムを駆使して他プレイヤーより速くゴールを目指す縦スクロール対戦アクションゲームです。
一画面を縦に分割しています。
画面を暗くしたり、操作を左右反転、移動速度アップ、ブロックが降ってくるギミックがあります。

### 背景
「Unityの教科書」という本で制作したClimeCloudを元に学内の3日間ゲームジャムで制作したゲームです。

### 制作環境

| 環境         | 内容                    |
|------------|-------------------------|
| 人数         | 3人(プログラマー2人,プランナー1人) |
| 使用ツール/言語 | Unity　C#                |
| 期間         | 12時間(3日間)              |
| 担当箇所     | お邪魔ギミック               |


#### 受賞
学内ゲームジャムで優勝

## 手続き型のダンジョン生成アルゴリズム  


### 内容
ドロネー三角形分割とプリム法を用いてのダンジョン生成です。  

### 参考URL
https://postd.cc/procedural-dungeon-generation-algorithm/   

http://www.deqnotes.net/acmicpc/prim/   

https://hadashia.hatenablog.com/entry/2018/10/11/194602

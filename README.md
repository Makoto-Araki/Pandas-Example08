# 時系列データをグラフ化
時系列データを折線グラフや棒グラフで表示

<br>

## 日本語化ライブラリを追加
```
pip install japanize_matplotlib
```

<br>

## 時系列データを表示
```
frame1
```
![画像1](./image01.png)

<br>

## 時系列データをグラフ化
```
frame1.plot()
```
![画像2](./image02.png)

<br>

## グラフにタイトル付与
```
frame1.plot(title='取引量の推移')
```
![画像3](./image03.png)

<br>

## グラフの色を緑・青・赤、点を四角、線を点線に変更
```
frame1.plot(title='取引量の推移', style=['gs-', 'bs-', 'rs-'])
```
![画像4](./image04.png)

<br>

## 棒グラフに変更
```
frame1.plot(kind='bar', title='取引量の推移', rot=55)
```
![画像5](./image05.png)

<br>

## 積上げ棒グラフに変更
```
frame1.plot(kind='bar', title='取引量の推移', rot=55, stacked=True)
```
![画像6](./image06.png)

<br>

## グラフを分割
```
frame1.plot(kind='bar', title='取引量の推移', subplots=True, figsize=(5,5))
```
![画像7](./image07.png)

<br>

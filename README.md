# Guess-the-number-game

## 概要
数字あてゲーム

## デモ
![output](https://github.com/Aki158/Guess-the-number-game/assets/119317071/73332152-0568-4e4b-ba21-47ce115ed08e)

## 説明
数字当てゲームです。

ランダムに設定された数字を推測してゲームのクリアを目指します。

ユーザーは、最初に 最小値/最大値/入力回数の上限値 を設定する必要があります。

正解の数字は、最小値から最大値までの範囲内でランダムな数字が生成されます。

初期設定/入力された数字の判定/メッセージの表示ができます。

## 学習内容
- データストリーム
- CLI 

## インストール

1. リポジトリをクローンする
```
git clone https://github.com/teraz1112/Guess-the-number-game.git
```

2. クローンしたリポジトリへ移動する
```
cd Guess-the-number-game
```

## 遊び方

1. ゲームを起動する
```
python3 guessTheNumberGame.py
```
2. ゲームの難易度を設定する。<br>今回は、下記のように設定しました。
    - Please enter a minimum value (n) : `2`
    - Please enter a maximum value (m) : `5`
    - Choose a difficulty level between 0 and 2<br>easy  (Input : 0)<br>medium(Input : 1)<br>hard  (Input : 2)<br>Input : `0`
3. ゲームを遊ぶ。<br>`Enter a number between 2 and 5 : `の後に正解の数字を推測しながら入力する。<br>入力回数は、手順2.で設定した難易度によって変わります。
4. ゲームを終了する。<br>ゲームのクリアに関わらず、最後まで遊ぶとゲームが自動的に終了します。<br>ゲームを途中でやめたくなった場合は、`Ctrl + c`を入力してください。

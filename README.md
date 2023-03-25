# hasegawa
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>スクリプトプログラミング演習</title>
<link rel="stylesheet" href="HB20A069.css">
<script src="hb20a069.js"></script>
</head>

<body>

<p id="time">
</p>

<p>
<div class="wakuarea">
<p class = "big">
<br>
<div>
<input type="number" id="number1"> +
<input type="number" id="number2">
<button onclick="Clicknumber()">計算！</button>
</p>

計算結果：<p id="result">

</div>
</div>
</div>
</p>
<p id="Bombe">

<img src="img/bakudan.png">
</p>

<p id="CountDown">
<button onclick="Trigger()">幸せになるボタン</button>
</p>

<div>
<button onclick="buttonTest()">アラートボタン</button>
</div>

<p>
<div>
<input type="text" id="Texbox1"value="テキストを入力しよう">
<button onclick="ClickTextbox1()">決定</button>
</div>
</p>

<p>
<div>
<input type="text" id="Texbox2"value="今夜食べたいものは？">
<button onclick="ClickTextbox2()">決定</button>
</div>
</p>

<h1>
<div id="DisplayTextbox2">
</div>
</h1>

<p>
<button onclick="iftest()">if文テスト</button>
</p>

<h1>HTMLの記述テストに昨日食べた晩御飯を書きます</h1>
<p>
昨日のご飯は<a href="https://www.osakac.ac.jp/">カレー</a>でした
<br>
<strong>今思えば先週何食べたっけ・・・</strong>

<p>
<div class="inlineblock">
<ul>
<li>ポテチ</li>
<li>焼き芋</li>
</ul>
</div>
</p>

<p>
<div class="inlineblock">
<table border="1">
<caption>最近のご飯まとめ</caption>
<tr>
<td></td><td>朝飯</td><td>昼飯</td><td>晩飯</td>
</tr>
<tr>
<td>4/22</td><td>なし</td><td>牛丼</td><td>どて焼き</td>
</tr>
</table>
</div>
</p>

<p>
<a href="https://www.osakac.ac.jp/"><img src="img/oecu_logo.jpg"></a>
</p>
<p>
<a href="#div2">div2へのジャンプだよ</a>
</p>
<div id="div1" class="sty1">
<h2>CSSを使う準備だよ</h2>
<p>
divで囲うことでグループ化させる事ができるのです
</p>
</div>
<div id="div2" class ="sty2">
<p>
上と下のdivではグループが別なのさ
</p>
</div>

<span id ="text"></span>


</body>
</html>

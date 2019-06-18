# software-architecture-auto-reload-js
SFCのソフトウェアアーキテクチャ(2019)の授業スライドを自動再読み込みする
多分sa19の部分を書き換えれば来年以降も使えるはず

ブックマークレットへの登録用
```
window.open('javascript:setInterval(function(){window.opener.location.href="https://vu5.sfc.keio.ac.jp/slide/index.php?page=top&mode=show&lecture=sa19&smode="},7000)');void(0);
```

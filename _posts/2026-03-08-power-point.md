---
title: "Power Pointの設定"
layout: post
tag: tips
---


## テンプレート
研究室や自分で作成したオリジナルのテンプレートをPower Pointで扱いやすくする．

1. pptxファイルでテンプレートの作成・編集（この時，規定のテキストボックスや図形も設定しておくとよい）
2. 1.のpptxファイルをテンプレートとして保存し，potxファイルで保存
3. 2のpotxファイルを'/Users/{your-username}/Library/Group Containers/UBF8T346G9.Office/User Content/Templates'に置いておけばPower Pointの初期画面の新規作成のところにPersonalとして表示される

pptxファイルを共有すれば共有された側が後で編集することができる．

## iguanaTex

[gitHub](https://github.com/Jonathan-LeRoux/IguanaTex){:target="_blank"}から自分の環境にあったものをインストールして，パスの設定を確認すればよい．

<body>
<p>Last updated: <time id="modified_date"></time></p>
<script>
const last = new Date(document.lastModified);
const viewDateText = last.getFullYear() + "年" + (last.getMonth() + 1) + "月" + (last.getDate()) + "日";
document.getElementById('modified_date').textContent = viewDateText;
</script>
</body> 

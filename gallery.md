---
title: "Gallery"
layout: page
---

<div style="text-align: center;"><img src="https://m20027.github.io/m20027/assets/images/IMG_0644.jpeg" width="30%"></div>

---
<body><p>Last updated: <time id="modified_date"></time></p>
<script>
// ステップ1：HTMLファイルの最終更新日を取得
const last = new Date(document.lastModified);
// ステップ3：上書き用の日付のテキストを作成
const viewDateText = last.getFullYear() + "/" + (last.getMonth() + 1) + "/" + (last.getDate());
// ステップ4：更新日の表示先のHTMLの"time"タグを上書き
document.getElementById('modified_date').textContent = viewDateText;
</script></body>

<small>&copy; 2025 Kazuaki OHYAMA</small>
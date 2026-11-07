# 關西國小 3D 校園導覽

新竹縣關西國小的 3D 校園示意模型（Three.js），可依樓層查看各棟教室，並連到 33 個 360° 實景點（環景照片來自 [360school](https://kingvincentwang.github.io/360school/)）。

線上瀏覽：https://kingvincentwang.github.io/gses-campus-3d/

## 調整建築或地點位置
座標以 Google 地圖衛星截圖的像素表示（1 px ≈ 0.55 公尺），修改 `index.html` 中的：
- `BUILDINGS`：各棟範圍 `r:[左, 上, 右, 下]`、樓層數、各樓層教室
- `SPOT_POS`：360° 地點 `[px, py, 樓層, 所屬建築]`

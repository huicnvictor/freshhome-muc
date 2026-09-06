清洁前后对比照片，来源：C:\Users\godha\Desktop\个人项目\清洁图片
命名规则：编号 + 字母，d/d1 = 清洁前，其他字母 = 清洁后（同一编号是同一个地方）

当前网站用的对应关系：
group1-bathroom       卫生间       (1d1 → 1b)
group2-room           房间         (2d1 → 2c)
group3-balcony        阳台         (3d1 → 3b)
group4-shower         淋浴间       (4d1 → 4b)
group5-whole          全屋整体     (5d + 5d1 → 5b + 5c + 5e，用户确认按整个公寓处理)
group6-showerhead     花洒除垢     (6d1 → 6b)
group7-kitchen        厨房         (7d1 → 7b)
group8-showertile     淋浴瓷砖     (8d1 → 8b)

以后要加新的一组对比图：
1. 把原图放进 C:\Users\godha\Desktop\个人项目\清洁图片，按 编号+字母 命名
2. 用 Pillow 压缩后放进这个 images 文件夹（原图太大，5-9MB一张，直接用会拖慢网页）
3. 去 index.html 的 before-after 板块复制一份 .ba-pair 结构，换上新文件名

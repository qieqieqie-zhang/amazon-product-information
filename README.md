# Amazon 商品信息采集技能

根据亚马逊商品链接或 ASIN，整理指定颜色变体的商品信息，并下载可获取的商品图片和视频。

## 使用

在 Codex 中调用 `$amazon-product-information`，提供亚马逊商品链接或 ASIN；可指定站点、颜色和保存目录。例如：

> 使用 $amazon-product-information 整理 ASIN B0FP983HN6 的黑黄色商品信息，下载图片和视频。

## 输出

默认创建 ASIN 文件夹，包含以 ASIN 命名的 HTML 商品信息页、主图、副图和可获取的视频。页面记录标题、颜色、五点描述、产品描述、商品参数和信息冲突；缺失或下载失败会注明。

## 依赖

需要本机 `C:/Users/Administrator/.workbuddy/skills/web-access/SKILL.md` 和可用的浏览器连接。该路径是当前环境配置，迁移到其他机器时应修改技能中的路径。网站登录、验证或媒体访问限制可能影响结果。

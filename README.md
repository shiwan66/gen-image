# 水浒传 AI 海报 · Water Margin AI Posters

本仓库收录 **108** 张 AI 生成《水浒传》人物竖版封面，分辨率 **720×1280**。

- 目录：`assets/shuihu/shuihu-batch01` … `shuihu-batch11`
- 清单：`manifests/shuihu-full-manifest.json`
- 许可：公开浏览与下载，无保密要求。

## 克隆

```bash
git clone https://github.com/shiwan66/gen-image.git
```

## 海报文件

若 `assets/shuihu/` 尚未出现，可在 GitHub **Actions → Import poster tarball** 中运行工作流，填写公开可访问的 `shuihu-108-posters.tar.gz` 下载地址；工作流会用仓库 `GITHUB_TOKEN` 提交 108 张 PNG。

也可在本机执行：

```bash
git clone https://github.com/shiwan66/gen-image.git
cd gen-image
# 从 Cursor Project store 拷贝 batch01–11 后：
git add assets/shuihu && git commit -m "Add posters" && git push
```

## 授权

AI 生成图像；使用时请遵守各模型服务条款与所在地法律。

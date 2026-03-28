# model_pic

存放模特参考照片和姿势图。

## 目录结构

```
model_pic/
  fullBody/     ← 全身照参考图
  halfBody/     ← 半身照参考图
```

## 命名规范

文件名对应 poses.ts 中的 `imagePath` 字段，例如：
- `fullBody/beach_01.jpg`
- `halfBody/cafe_01.jpg`

上传图片后，在 poses.ts 对应条目的 `imagePath` 字段填写相对路径即可显示。
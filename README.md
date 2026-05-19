# 我的私房菜 — 个人菜单

扫码即可查看菜单，免费托管在 GitHub Pages。

## 如何更新菜单

编辑 `menu.json` 文件即可：

```json
{
  "shopName": "我的私房菜",
  "categories": [
    {
      "name": "分类名称",
      "dishes": [
        {
          "id": 1,
          "name": "菜品名称",
          "image": "images/xxx.jpg",
          "description": "可选描述",
          "price": "可选价格"
        }
      ]
    }
  ]
}
```

## 添加新菜品步骤

1. 把菜品照片放入 `images/` 文件夹
2. 在 `menu.json` 的对应分类 dishes 数组中添加一条
3. 提交并推送到 GitHub

## 部署到 GitHub Pages

见下方部署指南。

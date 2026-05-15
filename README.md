# Mac-OvO.github.io

一个可直接部署到 GitHub Pages 的自用越狱源模板（拟态风格主页）。

## 功能
- 拟态风格首页（`index.html`）
- 基础 APT 仓库元数据（`Packages` / `Release`）
- 支持架构：`iphoneos-arm64`、`iphoneos-arm64e`

## 使用方式
1. 将你的 `.deb` 文件上传到仓库（建议放在 `debs/` 目录）。
2. 将每个包的信息追加到 `Packages` 文件。
3. 按需更新 `Release`（架构、描述、版本等）。
4. 在 Sileo / Zebra 添加：`https://mac-ovo.github.io/`

> 说明：这是一个简化模板，后续你可以加入签名、自动生成 Packages/Release 的脚本。

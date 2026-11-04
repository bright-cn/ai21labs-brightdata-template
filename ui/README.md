# Vite 与 HeroUI 模板

这是一个使用 Vite 和 HeroUI (v2) 创建应用程序的模板。

[在 CodeSandbox 上试用](https://githubbox.com/heroui-inc/vite-template)

## 使用的技术

- [Vite](https://vitejs.dev/guide/)
- [HeroUI](https://heroui.com)
- [Tailwind CSS](https://tailwindcss.com)
- [Tailwind Variants](https://tailwind-variants.org)
- [TypeScript](https://www.typescriptlang.org)
- [Framer Motion](https://www.framer.com/motion)

## 使用方法

要克隆项目，请运行以下命令：

```bash
git clone https://github.com/heroui-inc/vite-template.git
```

### 安装依赖项

你可以使用 `npm`、`yarn`、`pnpm`、`bun` 中的任意一种，以下是使用 `npm` 的示例：

```bash
npm install
```

### 运行开发服务器

```bash
npm run dev
```

### 设置 pnpm（可选）

如果你使用 `pnpm`，则需要将以下代码添加到 `.npmrc` 文件中：

```bash
public-hoist-pattern[]=*@heroui/*
```

修改 `.npmrc` 文件后，需要再次运行 `pnpm install`，以确保正确安装依赖项。

## 许可证

采用 [MIT 许可证](https://github.com/heroui-inc/vite-template/blob/main/LICENSE)。

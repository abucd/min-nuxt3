# 这是一套 min-nuxt3

## 依赖

> node 20.11.1 LST  
> pnpm 8.15.4  
> pnpm 淘宝镜像 https://registry.npmmirror.com

[去官网搜索 node 版本](https://nodejs.org/en)

### 注意，需要下载安装完 node 才可以运行下面东西

```bash
# 全局安装pnpm（可以加快下载速度）
npm i -g pnpm

# 设置pnpm淘宝镜像（可以加快下载速度）
pnpm config set registry https://registry.npmmirror.com
```

## 启动项目

```bash
# 安装项目依赖
pnpm i

# 本地启动
pnpm dev

# 本地测试生产环境启动
pnpm build
pnpm preview

## 打包相关

# 打包成静态
pnpm generate

# 打包成动态
pnpm build
```

### 下面的不用看

# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm run dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm run build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm run preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

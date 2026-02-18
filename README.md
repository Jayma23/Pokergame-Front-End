# Berkeley Poker — Live Table

扑克牌桌模拟界面，支持部署到多种平台。

## 快速部署（选一种即可）

### 方式一：Netlify Drop（最简单，无需命令行）

1. 打开 https://app.netlify.com/drop
2. 将整个 `berkeley-poker` 文件夹拖入页面
3. 几秒后获得一个在线链接，如 `https://xxx.netlify.app`

### 方式二：Vercel（需登录）

```bash
cd berkeley-poker
npx vercel login    # 按提示用浏览器登录
npx vercel          # 部署，会得到 https://xxx.vercel.app
```

### 方式三：Surge.sh（需注册）

```bash
cd berkeley-poker
npx surge .
# 首次会要求输入 email 和设置密码
# 部署后会得到 https://xxx.surge.sh
```

### 方式四：GitHub Pages（需 GitHub 账号）

1. 在 GitHub 创建新仓库，把 `berkeley-poker` 推上去
2. 进入仓库 → Settings → Pages
3. Source 选 `Deploy from a branch`
4. Branch 选 `main`，文件夹选 `/ (root)` 或创建 `docs` 子目录放 index.html
5. 保存后几分钟内会得到 `https://用户名.github.io/仓库名/`

---

## 本地预览

```bash
cd berkeley-poker
npx serve .
# 或
python3 -m http.server 8080
```

然后在浏览器打开 http://localhost:3000 或 http://localhost:8080

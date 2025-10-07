<h1 align="center">✨ 全栈聊天和视频通话应用 ✨</h1>

![Demo App](/frontend/public/screenshot-for-readme.png)

亮点：

- 🌐 实时消息传递，带有打字指示器和反应
- 📹 1对1和群组视频通话，支持屏幕共享和录制
- 🔐 JWT 认证和受保护路由
- 🌍 语言交换平台，拥有32种独特的UI主题
- ⚡ 技术栈：React + Express + MongoDB + TailwindCSS + TanStack Query
- 🧠 使用Zustand进行全局状态管理
- 🚨 错误处理（前端和后端）
- 🚀 免费部署
- 🎯 使用Stream等可扩展技术构建
- ⏳ 还有更多！

---

## 🧪 .env 设置

### 后端 (`/backend`)

```
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### 前端 (`/frontend`)

```
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## 🔧 运行后端

```bash
cd backend
npm install
npm run dev
```

## 💻 运行前端

```bash
cd frontend
npm install
npm run dev
```

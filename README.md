## Demo 使用说明

### 目录说明

```
├── README.md
├── lerna.json
├── package.json
└── packages
    ├── main       // 主应用（基座应用）
    ├── purehtml   // 微应用（纯 html 应用）
    ├── react      // 微应用 (react 应用)
    └── vue        // 微应用（vue 应用）
```

### 安装依赖

```bash
npm install
```

then:

```bash
npm run bootstrap
```


### 本地运行

```bash
npm start
```

浏览器打开 `http://localhost:7099` 即可体验微前端 Demo。
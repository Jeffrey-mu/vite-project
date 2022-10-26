# 添加`turbo.json`

```json
{
  "pipeline": {
    "build": {
      "outputs": ["dist/**"]
    },
    "lint": {
      "outputs": []
    }
  }
}
```

- 修改package.json
```json
{
  "scripts": {
    "build": "vite build",
    "lint": "tsc"
  }
}
```
- Try running build and lint with turbo:
```bash
npx turbo build lint
```
- Try running dev with turbo:
```bash
npx turbo build lint
```

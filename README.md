# 牌効率トレーナー

React + TypeScript + Vite で作った、少牌数の牌効率トレーニングアプリです。

## Local

```bash
npm install
npm test
npm run build
npm run dev
```

## Vercel Preview With GitHub

1. このプロジェクトを GitHub リポジトリへ push します。
2. Vercel で `Add New...` → `Project` を選び、GitHub リポジトリを import します。
3. Vercel の設定は自動検出されます。明示設定は `vercel.json` にあります。
   - Framework: Vite
   - Install Command: `npm install`
   - Build Command: `npm run build`
   - Output Directory: `dist`
4. 以後、GitHub に push または pull request を作ると Vercel Preview Deployment が作成されます。
5. GitHub の PR 画面に Vercel の Preview URL / Deployment Status が表示され、そのURLで出力結果をレビューできます。

## Notes

- `node_modules/` と `dist/` は GitHub に含めません。
- Vercel 側で Node.js 18 以上を使う想定です。

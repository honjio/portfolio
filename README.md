# nextjs

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## memo

### styled-components vs emotion

- styled-components と emotion で出来ることは大体同じ
- パフォーマンスの観点では styled-components < emotion
- SSR考慮の観点では styled-components < emotion
- ドキュメント量の観点では styled-components > emotion
- emotion/core では jsx pragma コメントが必要。
- css prop 記法ではなく styled component 記法であれば emotion/styled のみを使用すれば良い
- emotion/styled では jsx pragma コメントは必要ない

参考

- [Gatsby + netlify から next.js + zeit/nowに乗り換えようと試みて(未遂)得られた知見](https://www.terrier.dev/blog/2019/20191202000000-next-js/)
- [CSS-in-JSのライブラリとして「emotion」を選択している理由](https://qiita.com/__sakito__/items/d240840eef7123f62acf)
- [styled-components-vs-emotion](https://github.com/jsjoeio/styled-components-vs-emotion)
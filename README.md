# nextjs-cdk-amplify-starter
A starting point for some [GOSPEL](https://www.getrevue.co/profile/lzrs/issues/introducing-gospel-global-open-source-permissionless-enterprise-league-676392)-related apps. Technologies: TypeScript, Next.js 11, Tailwind CSS, Eslint, Prettier, CDK, Amplify. The CDK is adapted from [this repo](https://github.com/dabit3/next.js-cdk-amplify-workshop).

## Todo
1. Lerna
2. CD
3. Conventional commits
4. Convert into template or polish to be a usable starter kit

## Troubleshooting
If no cdk exports file is found:
1. `cd cdk`
2. `npm run build && cdk deploy -O ../web/cdk-exports.json`

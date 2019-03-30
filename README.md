# typescript-incremental-no-emit
https://github.com/Microsoft/TypeScript/issues/30661
## Steps
1. Run `npm install` or `yarn`
2. Run `npm run typecheck` or `yarn typecheck`
3. Result: `.tsbuildinfo` file was not created
4. Set `noEmit` to `false` in `tsconfig.json`
5. Run `npm run typecheck` or `yarn typecheck`
6. Result: `.tsbuildinfo` file was created

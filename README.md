# @ribeirolabs/package-template

## Setup

1. Update `PACKAGE_NAME` in `package.json`
2. Create Github repo
3. `npm i`
4. `npx semantic-release-cli setup`
5. Set `globalName` for the browser build in `scripts/build.js`
6. `mv github .github`

## React

1. `npm i -D react @types/react @testing-library/react`
2. Create `src/react/index.ts`
3. Update `tsconfig.json` to include `.tsx` file and `tsconfig.build.json` to include `src/react/index.ts`

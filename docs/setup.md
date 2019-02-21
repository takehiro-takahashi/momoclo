# setup

## install

```sh
yarn create nuxt-app app
```

## TypeScript setting

```sh
rm -rf node_modules package-lock.json
```

package.jsonのdependenciesからnuxtを削除して、以下コマンドを実行
(vue-property-decoratorは@Componentsデコレーター用)

```sh
npm install -S nuxt-ts vue-property-decorator
```

```sh
# npm update
npm install -g npm-check-updates
ncu -u
```

```sh
npm install -g typesync
typesync
```

*ncuコマンドやtypesyncコマンドが聞かないときは以下を実行してみる*

```sh
echo export PATH=$PATH:｀npm bin -g｀ >> ~/.bashrc
source ~/.bashrc
```

```sh
npm install
```

package.jsonの修正
scriptの `nuxt` となっている個所をすべて `nuxt-ts` に変更

```sh
npm run dev
```

tsconfig.jsonが無いと怒られるので、yで作成する

compilerOptionsに以下を追加

```json
"experimentalDecorators": true,
"allowJs": true,
```

```sh
npm run dev
```

## pug, stylus

```sh
# pug
yarn add -D pug pug-loader pug-plain-loader

# stylus
yarn add -D stylus stylus-loader

```

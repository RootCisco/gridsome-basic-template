# Gridsome Basic Tmeplate (for myself)

My basic template for getting started with [Gridsome](https://gridsome.org/).<br>
(changed starter-default as a base.)

*Gridsome version v0.7.x*

## Prerequisites

> - [Node.js v8.3+](https://nodejs.org/en/)
> - [Yarn](https://yarnpkg.com/)
>
> *You should have basic knowledge about HTML, CSS, Vue.js and how to use the Terminal. Knowing how GraphQL works is a plus, but not required. Gridsome is a great way to learn it.*
>
> reference by [Introduction - Gridsome](https://gridsome.org/docs/#prerequisites)

## Install and Start

### 1. Gridsome CLI tool を持ってなかったら、グローバルインストールしておく

    $ npm i -g @gridsome/cli
    OR
    $ yarn global add @gridsome/cli

### 2. このプロジェクトを`gridsome create`コマンドでインストールして始める

1. `gridsome create {my_project_name} cixocs/gridsome-basic-template`
2. `cd {my_project_name}`
3. `yarn dev` start local development server to `http://localhost:3000`
4. `yarn build` generate files in `dist/` folder
5. Happy coding 🎉🙌

## Note

1. pug, stylus は使えるようにしてます。

2. [ress (modern reset css)](https://github.com/filipelinhares/ress) でブラウザ CSS をリセットさせてます。<br>（お気に召さなかったら、別のものを入れてください）

3. prettier, eslint もある程度設定しているので、お好きに変更してください。<br>
   VSCode使用する前提で`.vscode`も置いてあります。
   > VSCodeプラグインをインストールして適用する必要があります！<br>
   > extensions.json 置いてあるので VSCode 上でアテンション出ると思います

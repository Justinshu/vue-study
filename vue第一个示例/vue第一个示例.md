# vue第一个示例

>  🍿拿到新项目开始步骤

1. 下载源码，解压
2. `cd` 到指定解压的目录，`npm install`下载项目依赖包(如果报错可能是`npm`版本不对,执行`npm rebuild`)
3. `npm run dev` `npm start`启动当前项目服务器
4. [淘宝镜像](http://npm.taobao.org/)（`cnpm`）命令：` npm install -g cnpm --registry=https://registry.npm.taobao.org`

&nbsp;

>  🍿开发vue

1. `npm init`初始化项目,生成`package.json`（`npm init --yes`不会生成那些提示，项目名不要用中文命名）
2. `npm install 依赖 --save`下载依赖安装（下载生产环境下的`npm install 依赖 --save--dev`）
3. `npm run build`编译打包

&nbsp;

> 🍿其他命令

**npm安装模块**

- `npm install xxx`利用 `npm` 安装`xxx`模块到当前命令行所在目录；
- `npm install -g xxx`利用`npm`安装全局模块`xxx`；

&nbsp;

**本地安装时将模块写入package.json中**

- `npm install xxx`安装但不写入`package.json`；
- `npm install xxx -–save`安装并写入`package.json`的`”dependencies”`中；
- `npm install xxx -–save--dev`安装并写入`package.json`的`”devDependencies”`中;

&nbsp;

**npm 删除模块**

* `npm uninstall xxx`删除`xxx`模块； 
* `npm uninstall -g xxx`删除全局模块`xxx`；


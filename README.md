# vue-template
一个基于Vue2 + TypeScript并使用ESLint | Prettier统一格式的代码模板

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## 备注
1. 解决了强迫症对代码格式统一的需求
2. ESLint用于检查代码问题并标记，Prettier用于静默格式化代码
3. 希望这个template能用久一点
4. `shims-vue.d.ts`帮助IDE了解以`.vue`结尾的文件是什么。当你在IDE启用`jsx`语法支持来写JSX风格的`TypeScript`代码时，`shims-tsx.d.ts`允许你使用`.tsx`文件。参考：[StackOverflow](https://stackoverflow.com/questions/54622621/what-does-the-shims-tsx-d-ts-file-do-in-a-vue-typescript-project)
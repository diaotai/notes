# 如何在 typescript 里使用 jest
1. 首先，项目里得有 typescript
```
yarn add -D typescript
```
2. 安装 jest 相关依赖
```
yarn add jest ts-jest @types/jest -D
```
3. 生成 jest 配置文件
```
npx ts-jest config:init
```
4. 生成测试报告
配置文件里把 collectCoverage 设置为 true
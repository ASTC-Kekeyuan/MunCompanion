# MunCompanion

Lwz突发奇想想做个MUN的辅助软件

然后就有了这个仓库

暂定采用Electron，同时作为我的Electron+js练手项目，暂时没有较为明确的开发计划

# Build Instruction

## Building Requirements

- node v12+
- npm

```bash
npm i --save-dev electron
npm install
```

## Run

```bash
npm run start
```

## Pack

```
npm install electron-packager -g
electron-packager . --icon=icon.ico --out=./out/ --overwrite
```

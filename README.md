# README
1. Github 找到ssr_subscrible_tool项目，将SSR链接写入note.txt文件， commit changes
2. netlify 点击New Site from Git爬取github内容找到ssr_subscrible_tool
    Build Command 输入 npm run build
    Publish Directory 输入 dist
    Deploy site

Good luck, guys!

# SSR节点列表生成器
> 适配ios版shadowrocket，PC或Mac版小飞机,

## 说明
- `/dist `位节点生成的目录,这个目录是给[netlify](https://app.netlify.com/)应用的
- `node.txt`为SS或SSR节点列表文件(支持类bash脚本注释，举个栗子: `# 注释`)
- `app.js`为项目的核心逻辑

如果你有什么问题，Please open an issues


## 更新说明
- 支持SS或者SSR

## 问题
- 据反映安卓或者Windows客户端可能无法订阅成功，请为添加的每一个节点设置相同的**分组**


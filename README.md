# 哔哩哔哩虚拟区字幕组组长抽卡模拟器

[原项目：arknights](https://github.com/lollipopnougat/arknights)<br>

该项目目前为0.3测试版 仅仅是能跑 还需要大量的文本改动和美工 这不来个组长干活？

之后版本会使用新的背景以及字体 并且卡池会持续更新（前提是有美工）

## 使用方法

### 如果要体验模拟抽卡，请访问托管页面：<br>

[Vercel](https://draw-card.vercel.app/)<br>
[腾讯云（大概)]暂无<br>

### 目前卡池

6星：雾羽，丫丫，高桥，星间，葬葬<br>
5星：琉音，Yasukii，BCC，亿万Hideki，王子<br>
4星：莽莽，黑色年代记，BJB，蓝蓝，影妹<br>
3星：红叶，小乙

### 如果对此项目本身感兴趣

<s>此项目是采用 `typescript` + `less` + `html` 进行前端开发的小型静态页面，使用 `webpack` 构建打包

如果想修改ts代码(位于 `src/ts` 文件夹内的 `main.ts` )以后运行，需要安装 `Node.js` 的环境

clone项目

```bash
git clone https://github.com/SHDocter/Draw_card.git
```

随后在项目根目录执行

```bash
npm i
```

- 修改完成以后编译

由于使用了 `webpack`，故直接在项目目录控制台输入

```bash
npm run build
```

随后打开`dist/index.html`或进行静态托管即可看到效果</s><br>

建议直接静态托管

### 关于卡池

卡池仅限于圈子里互相认识的组长 并且因为缺少美工 卡池不全 星级只是恶趣味 除了红叶真的是懒狗 其余组长都是dalao

## 写在最后

感谢arknights大佬的源码 感谢某不愿透露姓名的好心人的初版美工 感谢影妹的美工 感谢各位组长不车之恩
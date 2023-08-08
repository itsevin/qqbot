# 猜单词

## 功能介绍

根据残缺字母猜单词

## 触发指令

- ```@机器人 + 猜单词```
- ```wordle```

> 开始游戏的第二种指令

- ```@机器人 + 猜单词 + -l --length + -d --dic```
  - ```@机器人猜单词 -l8 -dGRE```

> 可使用 -l --length 指定单词长度，默认为 5
> 可使用 -d --dic 指定词典，默认为 CET4
> 支持的词典：GRE、考研、GMAT、专四、TOEFL、SAT、专八、IELTS、CET4、CET6

- ```结束```
- ```提示```

## 游戏规则

绿色块代表此单词中有此字母且位置正确

黄色块代表此单词中有此字母，但该字母所处位置不对

灰色块代表此单词中没有此字母

猜出单词或用光次数则游戏结束

## 功能展示

![猜成语](http://img.sevin.cn/i/2022/12/28/63ac13695a306.png)

## 插件来源

https://github.com/noneplugin/nonebot-plugin-wordle
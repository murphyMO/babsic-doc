# css 可用特性 -- 与css next无关
```
resolve:
    图片引入: background: resolve('xxx.png');    
```
```
inline: 将图片编译为 base64 格式
    baseurl: backround: inline('xxx.png')
```
```
body {
  width: width('xx.png'); /* 320px */
  height: height('xx.png'); /* 240px */
  background-size: size('xx.png'); /* 320px 240px */
}

body {
  width: width('xx.png'); /* 320px */
  height: height('xx.png'); /* 240px */
  background-size: size('xx'); /* 320px 240px */
}
```

Rucksack

- 自适应模式

```
    font-size: responsive [min-font-size] [max-font-size]
    font-range: [lower-bound] [upper-bound]
    
    例:
    html {
      font-size: responsive 12px 21px;
      font-range: 420px 1280px;
    }
    or
    html {
      font-size: responsive;
      min-font-size: 12px;
      max-font-size: 21px;
      lower-font-range: 420px;
      upper-font-range: 1280px;
    }
```
- position简写

```
- position: [type] [all];
- position: [type] [y] [x];
- position: [type] [top] [x] [bottom];
- position: [type] [top] [right] [bottom] [left];

例:
.foo {
  position: absolute 0;
}

.bar {
  position: relative 20% auto;
}

.baz {
  position: fixed 0 20px 10px;
}
```

- 选择器

```
:at-least
例:
li:at-least(4) {
  color: blue;
}

:at-most
例:
li:at-most(4) {
  color: blue;
}

:between
例:
li:between(4, 6) {
  color: blue;
}

:exactly
例:
li:exactly(4) {
  color: blue;
}
```

- Native Clearfix

```
fix: IE8+
fix-legacy: IE6/7 +
.foo {
  clear: fix;
}

.bar {
  clear: fix-legacy;
}
```

- 颜色快捷语法

```
例: 
.foo {
  color: rgba(#fff, 0.8);
}
```

- 属性别名

```
例: 
@alias {
  fs: font-size;
  fw: font-weight;
}
.foo {
  fs: 16px;
  fw: bold;
}

等于:
.foo {
  font-size: 16px;
  font-weight: bold
}

不支持属性内加入别名
@alias {
  op: opacity;
}

.foo {
  /* Not supported! */
  transition: op 300ms ease;
}
```



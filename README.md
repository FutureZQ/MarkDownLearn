# Learn Markdown
[toc]
***
## 1. 标题测试 
### 1.1 level 2 title
#### 1.1.1 level 3 title
## 2. 段落格式
### 2.1 段落
段落1，1234

段落2，4321
### 2.2 格式
*斜体*  
_斜体_  
**粗体**  
__粗体__  
***粗斜体***  
___粗斜体___

### 2.3 分隔线
***
分割内容1
***
分割内容2
***

### 2.4 删除线
~~***作者是傻逼***~~

### 2.5 下划线
<u>点我领取红包</u>

### 2.6 脚注
百度可能是中国访问量最大的网站 [^神奇的网站]

[^神奇的网站]: www.baidu.com

## 3. 列表
### 3.1 无序列表
- 天气不错
- 空气挺好
- 约会地点很安静
- 女孩子的手很滑
- 就是闹铃要点吵
  
### 3.2 有序列表
1. 点亮手机
   - 指纹
   - 头像
   - 密码 
1. 打开微信
   - 发消息给她？
   - 还是发消息给她？ 
2. 发一条微信
   - 早上好
3. 石沉大海
4. 扭头继续睡
   
## 4. 区块(引用)
### 4.1 区块中使用列表
周末日常
> 1. 起床日常问候
> > - 早啊
> > - 起了么
> > - 在干嘛？
> > - 吃了嘛？
> 2. 打游戏
> 3. 看电影
> 4. 学习
> 5. 睡觉

### 4.2 列表中使用区块
工作日常
1. 起床
2. 晨跑打卡
3. 上班摸鱼
4. 啥事没干所以加班
5. 愉快下班
6. 晚上问候
    > 睡了么
    > 在干啥
    > 晚安\^_\^

## 5. MarkDown 代码
### 5.1 行内代码
PhP是世界上最好的语言 `<?php`
### 5.2 代码区块
各种Hello World  
**Python:**
```python
print 'Hello World'
```
**C:**
```C
printf("Hello World");
```
**C++:**
```C++
cout << "Hello World" << endl;
```

## 6. 链接
### 6.1 普通链接
- [你希望的网站](www.baidu.com)
- [404](www.google.com)
- <https://www.qq.com>
  
### 6.2 变量形式
- [Google][googleWeb]
- [Baidu][BaiduWeb]

[googleWeb]: http://www.google.com/
[BaiduWeb]: http://www.baidu.com/


## 7. 图片
**央视新闻图片1：**
![图片1](http://img2015.zdface.com/20200825/b4969d52ed4f416a0a1c79e899784df5.jpg "央视新闻图片1")

**央视新闻图片2：**
![图片2][央视新闻图片2]

[央视新闻图片2]: https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1600016737772&di=deef7039f561890ce300d0da42cb64f5&imgtype=0&src=http%3A%2F%2Fp6.itc.cn%2Fimages01%2F20200905%2F703b237aae444ecdb4986315f84e9837.jpeg

**央视新闻图片3：**  
<img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1600016737765&di=2acbae8fcd469ada1700e2a13d1a49fb&imgtype=0&src=http%3A%2F%2Fqqpublic.qpic.cn%2Fqq_public%2F0%2F0-2653060761-A4B8FBFE5B12A093C892FFCED042BEEB%2F0%3Ffmt%3Djpg%26size%3D30%26h%3D307%26w%3D539%26ppv%3D1" width="50%">

## 8. 表格

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |


## 9. 其他
### 9.1 数学公式
![](https://latex.codecogs.com/gif.latex?%5Cmathbf%7BV%7D_1%20%5Ctimes%20%5Cmathbf%7BV%7D_2%20%3D%20%5Cbegin%7Bvmatrix%7D%20%5Cmathbf%7Bi%7D%20%26%20%5Cmathbf%7Bj%7D%20%26%20%5Cmathbf%7Bk%7D%20%5C%5C%5Cfrac%7B%5Cpartial%20X%7D%7B%5Cpartial%20u%7D%20%26%20%5Cfrac%7B%5Cpartial%20Y%7D%7B%5Cpartial%20u%7D%20%26%200%20%5C%5C%5Cfrac%7B%5Cpartial%20X%7D%7B%5Cpartial%20v%7D%20%26%20%5Cfrac%7B%5Cpartial%20Y%7D%7B%5Cpartial%20v%7D%20%26%200%20%5C%5C%5Cend%7Bvmatrix%7D)

<!-- $$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$ -->
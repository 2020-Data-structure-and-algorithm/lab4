# Lab 4

## 教学团队
### 教师：郑骁庆
联系方式：[zhengxq@fudan.edu.cn](http://zhengxq@fudan.edu.cn)
### 助教：
- 陈雷远 [20210240034@fudan.edu.cn](http://20210240034@fudan.edu.cn) 
- 徐健涵 [20210240021@fudan.edu.cn](http://20210240021@fudan.edu.cn) 


## 任务

- 覆盖子串

## 获取及提交lab

**获取**：通过 `https://github.com/2020-Data-structure-and-algorithm/lab4`，获取。

**提交**：将提交物放到自己lab4的文件夹中，将文件夹压缩，压缩文件名应为你的 `学号_姓名` （如`20210240034_陈雷远`），提交至 `FTP` 站点（`ftp://10.12.5.33`）本课程文件夹的`work_upload/lab4` 文件夹下。

**提交物**：本课程要求使用java或python语言完成，本次lab如果用java语言完成需提交`Solution.java` ；python语言需提交`solution.py`。本次实验需要提交说明文档，请大家注意。

**截止时间**：2020年10月25日 23：59：59

## 覆盖子串
### 问题描述
针对给定的字符串S与字符串T，要求设计一种算法，查找S中包含T所有字符的最小子串，若有则输出子串，若没有则输出空字符串。
注意，S、T中字符均为大写，且T中字符可重复。\
需要提交说明文档来解释自己算法的复杂度。

### 示例：
```
输入：
S=ASODFNOASF,  T=AA,
输出：
“ASODFNOA”
输入：
S=ADOBECODEBANC, T=ABC
输出：
“BANC”
输入：
S=A, T=AA
输出：
“”

 ```

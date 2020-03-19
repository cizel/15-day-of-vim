# 30-day-of-vim

在这30天里，每天使用一个番茄钟(25分钟)的时间阅读《Practical Vim》并实践练习 Vim 的一些技巧。

开始时间：`2020.03.19` | 结束时间: `2020.06.27`

## Day 1 

> 时间：2020.03.19 | 阅读完成《Practical Vim》第一章 VIM 的解决问题的方式

其中一个重要的原则: 不要重复自己（Don't Repeat Yourself）

- 用 Dot(.) 来重复上一次执行的命令
- 常用的组合插入方式 (`C`, `s`, `S`, `I`, `A`, `o`, `O`) 分别代表 （`c$`, `cl`, `^C`, `^i`, `$a`, `A<CR>`, `ko`）
- 常用动作已经回退方式 `({edit} . u)`, `(f{char}/t{char} ; ,)`, `(/pattern<CR> n N)`, `(qx{changes}q @x u)` 

# exercism_ocaml

个人 OCaml 练习记录，按 Exercism 练习名和解答版本组织。目前收录一个闰年判断练习。

## 练习索引

| 练习 | 源码 | 内容 |
| --- | --- | --- |
| Leap | [leap.ml](solutions/ocaml/leap/1/leap.ml) | 按公历规则判断年份是否为闰年 |

目录格式为 `solutions/ocaml/<练习名>/<版本>/`。

## 本地查看与运行

安装 OCaml 后，在仓库根目录启动交互环境：

```sh
ocaml
```

将下面内容输入 OCaml REPL：

```ocaml
#use "solutions/ocaml/leap/1/leap.ml";;
leap_year 2000;; (* true *)
leap_year 1900;; (* false *)
leap_year 2024;; (* true *)
```

当前仓库仅包含解答源码，未收录 Exercism 题目说明、官方测试或 Dune 工程配置。上面的例子用于手动检查函数行为。

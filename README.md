有问题文件：default.withproblem.html
无问题文件：default.noproblem.html

data模块是 cookie、store、json三个模块的*build

再本地随便搭个环境，测试两个文件，观察console.log出来的内容，即可看出问题。
    default.withproblem.html log出来的是json模块
    default.noproblem.html log出来的是data模块



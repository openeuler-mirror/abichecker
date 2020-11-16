# abichecker

#### 介绍
abichecker为ABI兼容性检查工具，该工具主要调用[abi-compliance-checker](https://github.com/lvc/abi-dumper)、[abi-dumper](https://github.com/lvc/abi-dumper)工具接口，分析rpm包、debuginfo包，实现ABI兼容性检查。

#### 安装教程

1.  安装abi-dumper、abi-compliance-checker工具。
```shell
yum install -y abi-dumper abi-compliance-checker
```
2.  下载abichecker.py脚本。

#### 使用说明

1.  创建工作目录：`/root/checkdir/`，rpm包存放目录`libfoo`；
2.  将`libfoo`的rpm包、debuginfo包存放到目录`libfoo`；
3.  执行`python abichecker.py 'libfoo' '/root/checkdir/'`；
4.  ABI检查结果存放在`/root/checkdir/libfoo/compat_reports`目录下。

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 码云特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5.  码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)

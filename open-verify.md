# 《以果壳cache为例，介绍如何创建基于chisel的DUT》的简单记录
[here](https://open-verify.cc/mlvp/docs/basic/create_dut/)

## mill
链接挂了，[here](https://mill-build.org/mill/cli/installation-ide.html#_other_installation_methods)。

```bash
mkdir ~/.local/bin/
sh -c "curl -L https://github.com/com-lihaoyi/mill/releases/download/0.12.5/0.12.5 > ~/.local/bin/mill && chmod +x ~/.local/bin/mill"

```
## openjdk
```sudo apt install openjdk-17-jdk```

## NutShell
有一个env的shell脚本运行下，然后记得make。

## cache-ut
记得在cache-ut路径下添加`.mill-version`否则不成功。可以从NutShell中复制一份出来

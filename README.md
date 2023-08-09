# 销服工作手册提纲

# 基础知识
## 算能公司介绍
算能 致力于成为全球领先的通用算力提供商
专注于AI、RISC-V CPU等**算力产品**的研发和推广应用，以自研产品为核心打造了覆盖“云、边、端”的全场景应用矩阵 ，为城市大脑、智算中心、智慧安防、智慧交通、安全生产、工业质检、智能终端等应用提供算力产品及整体解决方案 。公司在北京、上海、深圳、青岛、厦门等国内 10 多个城市及美国、新加坡等国家设有研发中心
### [算能官网](https://www.sophgo.com/)

## 算能产品介绍
### [BM1684](#bm1684详情)
### [BM1684X](#bm1684x详情)
### [SE5](#se5详情)
### [SM5](#sm5详情)
### [SE6](#se6详情)
### [SE7](#se7详情)
### [SM7](#sm7详情)
### [SE8](#se8详情)

## 计算机基础
### CPU
**CPU，即中央处理器（Central Processing Unit）**，是计算机系统中的主要硬件组件之一，被认为是计算机的"大脑"。它负责执行计算机程序中的指令，控制数据的流动，并协调计算机系统的各个部件之间的工作。

CPU有以下几个主要功能：

1. **指令执行：** CPU能够读取并执行计算机程序中的指令，这些指令通常以二进制代码的形式存储。CPU根据指令的类型和操作码执行各种计算、逻辑和数据处理操作。

2. **控制单元：** CPU包含一个控制单元，负责从内存中读取指令，解码指令内容，然后按照指令要求执行相应的操作。控制单元还负责协调其他部件的工作，确保指令按照正确的顺序和时间执行。

3. **算术逻辑单元（ALU）：** ALU是CPU的一个子部件，负责执行各种算术（加法、减法等）和逻辑（与、或、非等）操作，用于处理数据。

4. **寄存器：** 寄存器是位于CPU内部的小型存储单元，用于暂时保存数据和指令。不同类型的寄存器用于不同的目的，如存储临时数据、指令计数器等。

5. **时钟：** CPU内部有一个时钟系统，它以固定的速度产生脉冲信号，用于同步各个部件的工作节奏，确保指令的执行按照正确的顺序和时间进行。

6. **缓存：** 缓存是位于CPU内部的高速存储器，用于临时存储常用的数据和指令，以加快数据访问速度，提高系统性能。

CPU的性能通常由时钟频率、核心数量、架构设计等因素决定。随着技术的进步，CPU设计不断演化，以提供更高的计算能力和效率。不同类型的计算机和设备可能使用不同架构和型号的CPU。

### GPU
**GPU，即图形处理器（Graphics Processing Unit）**，是一种专门设计用于处理图形和图像计算任务的硬件组件。它最初是为了加速图形渲染而开发的，但随着时间的推移，GPU的功能逐渐扩展，现在它还被广泛用于并行计算、科学计算、深度学习等领域。

GPU具有以下几个主要特点和功能：

1. **并行处理：** GPU设计用于处理大量的数据并行操作，这使得它在某些类型的计算任务中比传统的中央处理器（CPU）更加高效。GPU可以同时执行多个操作，从而加速计算过程。

2. **图形渲染：** 最初，GPU主要用于图形渲染，即将计算机生成的图形和图像数据转化为可视化的图像，以供显示在屏幕上。现代GPU在这方面具有强大的处理能力，可以支持高分辨率、逼真的图形效果和流畅的动画。

3. **并行计算：** 由于其并行处理的特性，GPU在许多科学计算、数值模拟和仿真等领域也得到了广泛应用。它能够同时处理大规模的数据，加快复杂计算任务的完成速度。

4. **深度学习和人工智能：** 近年来，GPU在深度学习和人工智能领域的应用急剧增加。深度学习模型的训练过程涉及大量的矩阵计算，而GPU的并行计算能力能够显著加速这些计算，使得模型训练时间大幅缩短。

5. **多核心结构：** 现代GPU通常具有多个核心，每个核心可以独立执行任务。这使得GPU在处理多个任务或线程时更加高效，同时也有助于并行计算。

总之，GPU在图形处理、并行计算和深度学习等领域发挥着重要作用，它已经成为许多计算机系统中不可或缺的组件之一。

### TPU
**TPU，全称为Tensor Processing Unit（张量处理单元）**，是由谷歌公司设计的一种专门用于加速人工智能工作负载的硬件加速器。TPU最初于2016年发布，旨在提供对于机器学习和深度学习任务的高效处理能力。

TPU具有以下几个主要特点和功能：

1. **专为张量计算而设计：** TPU的硬件架构专门优化了张量计算，这是深度学习中常见的运算类型。TPU通过高效的矩阵运算和并行处理，能够加速神经网络的训练和推理过程。

2. **高性能：** TPU的设计旨在提供高性能的人工智能计算能力。它的速度和效率使得在训练大型深度学习模型时能够显著减少计算时间，从而提高开发者的工作效率。

3. **硬件加速：** 与通用的中央处理器（CPU）和图形处理器（GPU）不同，TPU是专门为人工智能工作负载而设计的加速器。它在处理深度学习任务时能够表现出色，但在其他通用计算任务上可能不如CPU或GPU。

4. **云计算支持：** 谷歌将TPU集成到其云计算平台中，使得用户可以租用TPU资源来加速其人工智能工作负载。这使得开发者无需购买昂贵的硬件设备，而是可以在云上灵活使用TPU的计算能力。

5. **深度学习加速：** TPU在深度学习领域尤其表现出色，特别是在训练大型神经网络时。由于深度学习模型的计算密集性，TPU的硬件加速可以帮助减少训练时间。

需要注意的是，TPU是一种专用的硬件加速器，适用于特定类型的计算任务，特别是与人工智能和深度学习相关的任务。虽然TPU在特定情况下能够显著提高性能，但它并不适用于所有类型的计算工作。

### NPU
**NPU，全称为Neural Processing Unit（神经网络处理单元）**，是一种专门设计用于加速人工智能和神经网络计算任务的硬件加速器。与传统的中央处理器（CPU）和图形处理器（GPU）相比，NPU专注于高效处理与神经网络相关的运算，如矩阵乘法、卷积操作等，以加速深度学习和人工智能应用。

NPU具有以下几个主要特点和功能：

1. **神经网络优化：** NPU的硬件架构经过优化，旨在高效地执行神经网络中的运算。这包括前向传播、反向传播等与深度学习相关的操作。

2. **高性能计算：** NPU设计用于高性能计算，特别是在处理大规模神经网络时表现出色。它能够加速复杂的张量计算和卷积运算，从而加快模型训练和推理过程。

3. **低功耗：** NPU在设计上通常注重低功耗，这使得它在移动设备和嵌入式系统中具有优势。它能够在较小的能耗下完成大量计算任务，从而延长设备的电池寿命。

4. **特定应用领域：** NPU通常针对特定的应用领域进行优化，如计算机视觉、自然语言处理、语音识别等。这使得NPU在处理特定类型的数据和任务时能够更加高效。

5. **硬件加速：** 类似于GPU和TPU，NPU也是一种硬件加速器，专门用于处理神经网络计算。它可以在一些设备中作为附加的芯片或单元存在，以提供额外的计算能力。

NPU的出现和发展使得深度学习和人工智能应用在移动设备、嵌入式系统和其他资源受限的环境中变得更加可行。它们有助于加速模型的训练和推理，从而提高应用的性能和响应速度。不同制造商可能会开发不同架构和型号的NPU，以满足各种应用需求。

### 芯片频率
芯片频率是指计算机芯片（如中央处理器、图形处理器等）的工作时钟频率，通常以赫兹（Hz）为单位表示。它表示芯片每秒钟能够执行的振荡或周期数量，也就是处理器内部操作的速度。

在计算机芯片中，时钟信号以稳定的速率发出，控制芯片内部各个部件的工作节奏。每个时钟周期，芯片都会执行一系列操作，如读取、处理和写入数据，以及执行指令等。芯片频率越高，每秒内执行的操作数量就越多，从而通常表现为更高的计算性能。

然而，芯片频率并不是衡量性能的唯一因素。随着技术的进步，芯片架构、设计、制造工艺等方面的改进也会对性能产生影响。有时候，两个芯片虽然频率不同，但由于其他优化因素，低频率的芯片可能仍然具有相当的性能。

需要注意的是，随着时间的推移，芯片制造商不断努力提高性能，并不断增加芯片频率。然而，频率的提高也可能伴随着更高的能耗和热量产生，因此在设计和使用芯片时需要权衡性能和能效之间的关系。



***
## Linux基础
### Linux发行版
Linux 是一个开源的操作系统内核，但由于其开放性和灵活性，产生了许多不同的 Linux 发行版（Distribution，缩写为 "distro"）。每个发行版都基于 Linux 内核，并包含了一系列的工具、库、桌面环境和应用程序，以创建一个完整的操作系统。

####以下是一些常见的 Linux 发行版：

1.Ubuntu： 基于 Debian，被广泛用于桌面和服务器。它有不同的版本，如 Ubuntu Desktop、Ubuntu Server 等，以满足不同用途的需求。

2.Debian： 一个稳定、强大的发行版，被用于服务器和工作站。它也是许多其他发行版的基础。

3.Fedora： 由社区支持的发行版，强调最新的软件和技术。Fedora 也是 Red Hat Enterprise Linux（RHEL）的上游项目。

4.CentOS： 基于 RHEL 的重建版本，致力于提供一个免费的企业级操作系统。

5.openSUSE： 提供稳定和强大的桌面和服务器发行版，有两个主要版本：openSUSE Leap 和 openSUSE Tumbleweed（滚动发布）。

6.Arch Linux： 面向高级用户的发行版，强调简单性、定制性和文档。

7.Manjaro： 基于 Arch Linux，旨在为普通用户提供友好的体验，并提供了预配置的桌面环境。

8.Linux Mint： 基于 Ubuntu 或 Debian，专注于提供易于使用的桌面环境。

9.Elementary OS： 基于 Ubuntu，以精美的界面和用户友好的设计著称。

10.Kali Linux： 专为网络安全和渗透测试而设计的发行版，内置了各种安全工具。
### Linux命令行
Linux 命令行是在终端（Terminal）或命令行界面中输入和执行命令的方式，用于与 Linux 操作系统进行交互和管理。命令行是一个强大的工具，可以用于执行各种系统任务、文件操作、软件安装、配置管理等。
#### 基本操作指令
以下是一些常见的 Linux 命令行命令及其用法：

1.pwd： 显示当前工作目录的完整路径。
```
pwd
```
2.ls： 列出当前目录中的文件和子目录。
```
ls
ls -l  # 以长格式显示文件信息
ls -a  # 显示所有文件，包括隐藏文件
```
3.cd： 切换工作目录。
```
cd /path/to/directory  # 切换到指定目录
cd ..  # 切换到上级目录
```
4.mkdir： 创建新目录。
```
mkdir new_directory
```
5.rm： 删除文件或目录。
```
rm file.txt  # 删除文件
rm -r directory  # 递归删除目录及其内容
```
6.cp： 复制文件或目录。
```
cp file.txt new_location/  # 复制文件到指定目录
cp -r directory new_location/  # 递归复制目录及其内容
```
7.mv： 移动文件或重命名文件。
```
mv file.txt new_location/  # 移动文件到指定目录
mv old_name.txt new_name.txt  # 重命名文件
```
8.touch： 创建空文件或更新文件的访问时间。
```
touch file.txt
```
9.cat： 显示文件内容。
```
cat file.txt
```
10.echo： 在终端显示文本。
```
echo "Hello, world!"
```
11.grep： 在文件中搜索特定文本。
```
grep "search_text" file.txt
```
12.chmod： 修改文件或目录的权限。
```
chmod permissions file.txt
```
>r读取权限，数字4
>w写入权限，数字2
>x执行权限，数字1
>-不具备权限 数字0

13.chown： 修改文件或目录的所有者。
```
chown new_owner file.txt
```
14.ps： 显示运行的进程列表。
```
ps aux
```
15.kill： 终止运行中的进程。
```
kill process_id
```
16.apt-get 或 yum： 在 Debian/Ubuntu 或 CentOS/RHEL 等系统上安装和管理软件包。
```
sudo apt-get install package_name
sudo yum install package_name
```
17.df： 显示文件系统磁盘空间使用情况。
```
df -h
```
18.top 或 htop： 显示系统资源使用情况和运行中的进程。
```
top
htop
```
这只是一些常见的 Linux 命令行命令。Linux 命令行界面提供了丰富的功能和工具，可以满足各种系统管理和操作需求。可以通过命令行界面执行任务，也可以编写脚本自动化一系列操作

#### VIM编辑器
`vim`（Vi IMproved）是一款强大的文本编辑器，是 Unix-like 系统中常用的编辑工具之一。它是 vi（Visual Editor）编辑器的改进版本，提供了许多增强功能和功能，适用于编辑各种文本文件，包括代码、配置文件等。
以下是一些常见的 vim 编辑器的基本用法：

1.打开文件： 在终端中输入以下命令来打开一个文件：
```
vim filename
```
2.编辑模式： 打开文件后，默认处于命令模式（Command mode）。按下 `i` 进入插入模式（Insert mode），此时可以输入文本。
3.插入文本： 在插入模式下，键入所需的文本。按 `Esc` 键返回命令模式。
4.保存文件： 在命令模式下，输入 ：`w` 并按回车键保存文件。
5.保存并退出： 在命令模式下，输入 ：`wq` 并按回车键保存文件并退出 `vim`。
6.退出而不保存： 在命令模式下，输入 :`q!` 并按回车键，强制退出 `vim` 而不保存修改。
7.导航和移动光标： 在命令模式下使用以下键来移动光标：
* `h`：向左移动
* `j`：向下移动
* `k`：向上移动
* `l`：向右移动

8.删除文本： 在命令模式下使用以下命令来删除文本：
* `x`：删除光标所在位置的字符
* `dd`：删除光标所在行

9.复制和粘贴： 在命令模式下使用以下命令来复制和粘贴文本：
* `yy`：复制光标所在行
* `p`：粘贴复制的文本

10.搜索和替换： 在命令模式下使用以下命令来搜索和替换文本：
* `/search_term`：搜索指定的文本
* `:s/search_term/replace_term/g`：在整个文件中替换文本

11.撤销和重做： 在命令模式下使用以下命令来撤销和重做操作：
* `u`：撤销上一步操作
* `Ctrl + r`：重做上一步撤销的操作

12.分屏显示： 在命令模式下使用以下命令来分屏显示文本：
* `:split`：水平分屏
* `:vsplit`：垂直分屏

13.多文件编辑： 在命令模式下使用以下命令来编辑多个文件：
* `:e filename`：打开另一个文件
* `:n`：跳转到下一个文件
* `:prev` 或 `:N`：跳转到上一个文件

14.显示行号： 在命令模式下使用以下命令来显示行号：
* `:set number`

这只是一些 vim 编辑器的基本用法。vim 有非常丰富的功能和命令，可以用于高效编辑文本文件。用户可以通过 vim 的内置帮助系统（在命令模式下输入 :help 并按回车键）了解更多详细信息和高级用法。

## 网络基础

***

# 产品知识

## BM1684详情

***

## BM1684X详情

***

## CV181X、CV180X详情

***

## SOC模式-BM1684

### SE5详情
* 刷机手册
* 网络连接
* 串口连接
* 修改网络配置
* 自带工具

### SM5详情

### SE6详情

## SOC模式-BM1684X

### SE7详情

### SM7详情

### SE8详情

***

## PCIE模式-BM-1684

### SC5

### SC5+

## PCIE模式-BM-1684X

### SC7 HP75

### SC7 FP300

***

## 服务器

### SG6-6-A22

### SG6-6-A32

### SG6-10-B22

***
# 开发环境配置

***
# 算法知识

# 交付

# 售后

# 沟通话术
***
## 沟通表达基本原则
* 注意言语礼貌
* 内容表达清晰、具体
* 明确沟通目的
* 不正面拒绝客户
* 不随意向客户承诺
## 重点话术示例
### 客户支持前
**1. 拜访交流型**
* **向销售了解销售对销服支持的需求**
```
您好，这次与客户交流，您提出需要销服参与，是需要销服做哪方面的支持？
```
* **向销售了解客户信息及已经做过的交流**
```
您好，为届时更好的有针对性的与客户交流，需要提前向您了解一下这个客户的基本情况，主要业务场景，以及咱们已经与客户做过哪些方面的交流？
```
* **向销售了解客户基本诉求**
```
您好，这个客户对咱们公司的基本诉求是怎样的？希望我们提供什么样的产品或者服务？
```
* **向销售了解本次交流的基本目标**
```
您好，本次拜访客户交流，咱们这边希望达成什么目标？预计本次交流后，下一步是有什么计划安排？
```
**2. 产品支持型**
* **向销售了解客户使用的算能产品及应用场景**
```
您好，客户借测（或者采购）我们的什么产品？应用在什么场景下？
```
* **向销售了解目前项目状态**
```
您好，客户项目目前是什么状态？遇到了什么问题？刚拿到设备还是已经使用了一段时间？
```
### 客户支持（拜访）
**1. 面向客户**
* **介绍公司产品及方案**
```
具体参考对应的ppt材料学习
```
* **客户问题支持**

**(1)向客户释放文档资料**
```
以上资料请查收！如果还有其他任何问题，可以随时与我们交流。
```
**(2)客户的问题暂时不会回答**
```
很抱歉，您的这个问题我需要找后端的同事咨询，稍后给您回复！
```
**(3)客户的问题暂时没时间解答**
```
很抱歉，我现在开会，会后我会来回答您的问题。
```
**(4)客户的问题暂时没人回答（微信群）**
```
很抱歉，后端的同事在忙还没看到信息。我已经再次与他们联系，他们看到信息会给您回复。
```
**(5)客户对公司产品提出建议（待优化）**
```
很感谢您的提议，我会将您的建议反馈给公司产品部门。感谢您对我们产品的支持。
```
**(6)客户的需求暂时无法满足**
```
不好意思，稍等我们内部同步一下您这个需求，迟点回复您。
```
（这个情况，话术是一方面，更重要的是要与销售同步客户的需求，确定暂时无法满足，建议由销售来判断如何回应客户，是要求产品给予支持或者是从商务层面引导）
销服层面可以做的替代性方案回复：
```
您这个需求，目前您那边使用的产品（或平台）暂时实现不了。我们还有其他xxx产品（或者平台），可以通过xx方式满足您的要求，您看是否需要使用xxx产品（或者平台）？
```
**(7)远程连接支持**
```
您好，麻烦提供一个todesk远程链接，我们远程过去帮您看一下。因为公司有安全管理规定，禁用向日葵，还望您理解！
```
**2. 面向销售**
* **反馈技术支持进展**
```
您好，目前xxx客户的产品测试已经完成了1、2、3、。。。这些内容；目前遇到的问题是xxxx，已经提交xxxx处理。下一步的计划是xxxx。请知悉！
```
* **反馈客户需求（待商务决策）**
```
您好，xx客户提出希望实现xxx功能，目前我们标准产品（平台）我不包含这部分内容，客户这部分需求需要定制，请您评估决策是否需要在本次为客户实现xxx功能。
```
**3. 面向产品或生态**
* **技术支持需求**
```
您好，这边客户使用xxx产品，遇到xxx问题，需要麻烦您这边看一下，谢谢！
```
* **文档需求**
```
您好，这边客户使用xxx产品，需要xxx文档，我在企业微盘里没有找到，您这边是否有相关文档可以提供？谢谢！
```
* **客户需求或建议反馈**
```
您好，这边客户使用xxx产品，提出如下需求（或者建议），咱们是否可以实现？等您答复，谢谢！
```

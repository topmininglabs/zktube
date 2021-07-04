# zkTube 一键多开脚本（Ubuntu&CentOS）
### ===本脚本仅限TopMininG&amp;无产阶级社群用户使用===
#### ■ 一键脚本运行方法(整行复制粘贴执行)：
##### ・Ubuntu：
##### ___`sudo apt update && sudo apt-get install wget curl`___
##### ___`wget https://raw.githubusercontent.com/topmininglabs/zktube/main/topmining_zktube.sh && chmod +x ./topmining_zktube.sh && sudo ./topmining_zktube.sh`___
##### ・CentOS7：
##### ___`sudo yum update && sudo yum install wget curl`___
##### ___`wget https://raw.githubusercontent.com/topmininglabs/zktube/main/topmining_zktube.sh && chmod +x ./topmining_zktube.sh && sudo ./topmining_zktube.sh`___

##### ・CentOS8：
##### ___`sudo yum update --nobest && sudo yum install wget curl`___
##### ___`wget https://raw.githubusercontent.com/topmininglabs/zktube/main/topmining_zktube.sh && chmod +x ./topmining_zktube.sh && sudo ./topmining_zktube.sh`___


#### ■ 注意事项
##### 1：此脚本仅支持Ubuntu系统和CentOS系统
##### 2：运行脚本安装Docker并下载TopMininG专供zkTube镜像进行节点部署（TopMininG专供zkTube镜像为官方镜像的纯净打包版无任何修改可放心使用） 
##### 3：如因系统防火墙或云服务防火墙原因无法用次脚本下载安装Docker，请自行咨询服务商了解相应的Docker安装方法并手动安装Docker
##### 4：非TopMininG专供zkTube镜像部署的节点运行此脚本无效（TopMininG专供zkTube镜像为官方镜像的纯净打包版无任何修改可放心使用） 
##### 5：Ubuntu系统需先执行sudo apt update 确保系统软件依赖包为最新
##### 6：Centos系统需先执行sudo yum update 确保系统软件依赖包为最新
##### 7：此脚本虽可实现一地址多节点，鉴于官方尚未明确指出是否支持一个地址多开节点，使用此脚本多开的需自行承担风险（可能会有无收益或收益被清零的风险）
##### 8：关于系统配置要求，请参照下面官方说明：
###### zkTube矿机配置是建议32核64G（该配置上考虑了部分弹性预留，主要是为了避免复杂证明的计算可能带来的计算消耗溢出，引发Prover异常，从而触发prover挖矿惩罚机制，造成不必要的损失）。我们所采用的是当网络有使用的时候才会有区块产生，也就是当一个交易或者是一个任务抛出的时候需要带宽去抢任务，带宽越高抢到任务的概率越高，当任务抢到并计算完成的时候才会有奖励。真正做到了没有垃圾数据而且不会一直高消耗的空跑CPU。
##### 8：本脚本可无限制多开节点，请根据自身系统配置自行决定多开节点数量，操作选项（5）若输入1节点则只部署一个节点
##### 10：多开节点数量过多有可能导致系统奔溃或无法运行，请自行承担风险

#### ■ 操作说明
##### 1：选择操作选项（1）下载并安装Docker
##### 2：选择操作选项（2）下载并安装TopMininG专供zkTube镜像
##### 3：选择操作选项（3）创建revenue_address文件并设置收益地址
##### 4：选择操作选项（5）部署zkTube节点
#####

<img width="383" alt="スクリーンショット 2021-07-02 13 51 23" src="https://user-images.githubusercontent.com/86814869/124222477-cab03b80-db3c-11eb-8750-ceb1d1a42924.png">

##### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;-------------------------------------  
##### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;TopMininG & Proletariat无产阶级
##### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;联系方式:http://topmining.org
##### &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;------------------------------------- 
##### 
##### ===本脚本的命令仅支持用TopMininG专供zkTube镜像部署的节点===
##### ==专供zkTube镜像为官方镜像的纯净打包版无任何修改可放心使用==
##### 
##### (1) 安装Docker
##### (2) 下载/更新TopMininG专供zkTube最新镜像
##### (3) 创建revenue_address文件并设置收益地址
##### (4) 修改ETH收益地址
##### (5) 部署zkTube节点
##### (6) 查看收益地址
##### (7) 检查通过此脚本创建的zkTube节点运行状态
##### (8) 查看通过此脚本创建的单个zkTube节点运行日志
##### (9) 查看通过此脚本创建的所有zkTube节点运行日志
##### (10) 删除通过此脚本创建的revenue_address文件
##### (11) 删除通过此脚本部署的全部zkTube节点
##### (12) 删除通过此脚本下载的TopMininG专供zkTube镜像
##### (0) Exit
##### -----------------------------------------------------
#

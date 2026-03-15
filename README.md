# LLaMA-Factor
如何使用LLaMA-Factory库创建一个微调demo

## 一.下载LLaMA-Factory库
创建conda虚拟环境 ：
```bash
conda create -n LLaMA
```
执行install.sh文件下载LLaMA-Factory库
```bash
sh install.sh
```
下载完成后的文件夹目录如下：
```bash
--你的上级文件
    --finetune
    --LLaMA-Factory
        --examples
            --train_lora
            ...
        --data
            dataset_info.json
            ...
        ...
    --install.sh
```
其中直接修改examples/train_lora/xxx.yaml的配置即可实现对训练过程的配置（建议在LLaMA-Factory文件夹下面创建一个文件夹my_yaml用来存放自己的配置文件）



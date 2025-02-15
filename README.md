# TransferableUAL
Transferable Unintentional Action Localization with Language-guided Intention Translation (IEEE TPAMI 2025)

Created by [Jinglin Xu](https://xujinglin.github.io/), [Yongming Rao](https://raoyongming.github.io/), [Jie Zhou](https://scholar.google.com/citations?user=6a79aPwAAAAJ&hl=en), [Jiwen Lu](https://scholar.google.com/citations?user=TN8uDQoAAAAJ&hl=zh-CN)

This repository contains the FS-Falls dataset and PyTorch implementation for TransferableUAL.

[[Paper]](https://ieeexplore.ieee.org/abstract/document/10872809)

# Datasets

## OOPS

Please refer to [[OOPS]](https://github.com/cvlab-columbia/oops).

## FS-Falls
FS-Falls is a new dataset constructed in this work, which collects a variety of failed video instances from different figure skating competitions available on the International Skating Union website. The FS-Falls dataset contains 1517 video instances covering the short program and free skating in men’s single skating, women’s single skating, and pair skating.

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="FS-Falls-one.png" width = "100%" alt=""/>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
  	</div>
</center>
Fig. 1: Examples containing one fall in the FS-Falls dataset.

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="FS-Falls-multiple.png" width = "100%" alt=""/>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
  	</div>
</center>
Fig. 2: Examples containing multiple falls in the FS-Falls dataset.

All video instances are divided into two types: one fall during the action procedure and multiple falls throughout a series of action procedures. For the first type, there are 561 samples with one fall during the action procedure, as shown in Fig. 1, where the frames with yellow boxes indicate the annotated timestamps of the action switching from intentional to unintentional. For the second type, there are 956 samples with multiple falls, as shown in Fig. 2, where the segments with red, blue, green, and purple boxes represent a series of consecutive action procedures. There are 697, 214, and 45 video instances with two, three, and four falls (represented by frames with yellow boxes), respectively, as shown in Fig. 2 (a)-(c).

To download the FS-Falls dataset, please sign the Release Agreement and send it to Dr. Xu (xujinglinlove@gmail.com). By sending the application, you agree and acknowledge that you have read and understand the notice. After receiving your request, we will reply with the file and the corresponding guidelines!

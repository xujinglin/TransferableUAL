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

All video instances are divided into two types: one fall during the action procedure and multiple falls throughout a series of action procedures. For the first type, there are 561 samples with one fall during the action procedure, as shown in Fig. 1, where the frames with yellow boxes indicate the annotated timestamps of the action switching from intentional to unintentional. For the second type, there are 956 samples with multiple falls, as shown in Fig. 2, where the segments with red, blue, green, and purple boxes represent a series of consecutive action procedures. There are 697, 214, and 45 video instances with two, three, and four falls (represented by frames with yellow boxes), respectively, as shown in Fig. 2 (a)-(c).

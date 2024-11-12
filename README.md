# CemiFace
![CemiFace](image/Cemiface.jpg)
<!---
<p align="center">
    <img src="image/LAFS_aug_small_v3.pdf" alt="pdf" width="600"/>
</p> 
-->
<!--- 添加一下main图片，我没找到png版本的大图-->


Our paper  [CemiFace: Center-based Semi-hard Synthetic Face Generation for Face Recognition](https://arxiv.org/pdf/2409.18876)
is accepted to NeurIPS 2024, please stay tuned for the code, synthetic dataset and camera ready version. Thank you !


# Released Data

| Pretrained from | Data Volume | Link| AVG|
|----|----|----|----|
| CosFace         | 0.5M        | [link](https://1drv.ms/u/c/7bd58491c54e4351/EaQMx4ixEtlGpvsl0WGOekoBw0TibvUFJzVuzz6-W7Sx3g?e=EH0psS)| 92.71|
| CosFace         | 1.0M        | [link](https://1drv.ms/u/c/7bd58491c54e4351/EUafS0hDo7hCvknYZwEi2G0BmwpDCRAioViptHKVLZj4rA?e=HOQVnK)| 93.26 |
| CosFace         | 1.2M        | [extra 0.2m part](https://1drv.ms/u/c/7bd58491c54e4351/EQ3gDUQS6hxEmXF4VkrrNsoBF4OrBWLCfNX_JxNdWY3haA?e=2bL0Iz)| - |
|----|----|----|----|
| AdaFace         | 0.5M        | [link](https://1drv.ms/u/c/7bd58491c54e4351/Ee7v9_OPrNdNipo_7Sho1XoB74OgOPeeJ-ORzXMS8aW2bg?e=vj7rL0) | 92.30(reported in the paper)|
| AdaFace         | 1.0M        | -| - |
| AdaFace         | 1.2M        | -| - |


# Training Log
Training Logs for data derived from CosFace are released. Please download and use the following command to view the log

```
cat cemi_train_05m_log.o4607031
```

# TAO-Net

# TAO-Net: Task-Adaptive Operation Network for Image Restoration and Enhancement

<hr />

> **Abstract:** *Abstract—Recently, deep learning based models have been extensively applied to image restoration and enhancement tasks. However, existing approaches neglect the potential correlation among these tasks, and do not fully consider the different intensity factors of degradation which affect image quality. To this end, we propose Task-Adaptive Operation Network (TAO-Net) that stacks a series of operation blocks, guided by the supervised attention mechanism to adaptively enable the model to assign corresponding intensity weights for different degradation factors depending on the input signals. To better recover and preserve the accurate details during the repeated operations, we make full use of the image prior to intruduce structure refinement block as auxiliary information for reconstructing high-quality results.
Furthermore, feature aggregation block is also adopted to avoid feature interference caused by the direct concatenation between the backbone operation block and the auxiliary refinement block together. Extensive experiments on multiple benchmark datasets demonstrate that our proposed method outperforms previous baselines in image deraining and low-light image enhancement.* 
<hr />

## Network Architecture
![arch](https://github.com/zt-fan/TAO-Net/assets/90734659/a09773f9-0c95-486d-9fa5-c0a9b3cf0555)

## Deraining Results
![table1](https://github.com/zt-fan/TAO-Net/assets/90734659/ae7ffd89-1e21-4755-a946-fd6ec59e530f)
![img1](https://github.com/zt-fan/TAO-Net/assets/90734659/9c980e2b-81ea-4918-9964-a5f72604c575)


## LLIE Results
![table2](https://github.com/zt-fan/TAO-Net/assets/90734659/3dddae34-afdb-4547-b9de-fb96b6eb3a73)
![img2](https://github.com/zt-fan/TAO-Net/assets/90734659/4de3ff98-021d-4ddb-9510-91e146c97810)

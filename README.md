# 清冷唯美 · NovelAI V5 画师串

*Cool Elegance — a NovelAI V5 artist mix for muted colors, fine linework, and soft skin shading.*

整体偏清冷、低饱和，皮肤的明暗过渡柔和，发丝和衣装边缘保留细线条。用这组权重试过浅色窗光和冷色幻想场景，肤色会随场景光线在暖杏粉和冷象牙白之间变化。

## 画师串

```text
1.05::artist:wanke ::, 0.65::artist:misaka 12003-gou ::, 0.70::artist:liduke ::
```

复制到正向提示词中，搭配自己的角色、服装和场景描述。`数值::标签 ::` 是 NovelAI 的[数值权重写法](https://docs.novelai.net/en/image/strengthening-weakening/)。

## 实测示例

| 暖色窗光 | 冷色幻想 |
| :---: | :---: |
| [<img src="./warm-window-light.png" alt="暖色窗光下的银白长发角色" width="350">](./warm-window-light.png) | [<img src="./cool-fantasy.png" alt="冷色幻想场景中的银白长发角色" width="350">](./cool-fantasy.png) |
| 杏粉肤色与柔和的亮部过渡。 | 冷象牙肤色与淡紫灰阴影。 |

## 两张实测图共用的参数

| 设置 | 实测值 |
| --- | --- |
| 模型 | NovelAI Diffusion V5 Full |
| 尺寸 | 832 × 1216 |
| Steps | 24 |
| Prompt Guidance | 6 |
| CFG Rescale | 1 |
| Sampler | DPM++ 2M SDE (`k_dpmpp_2m_sde`) |
| Noise Schedule | `karras` |

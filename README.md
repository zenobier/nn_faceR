# nn_faceR

## modeling

#### data collect

收集包含各种眼睛颜色的图像数据集，并将图像标记为 Normal、Blue、Brown、Gray 和 Yellow。

#### data preprocess

调整图像大小（例如，224x224）。

进行数据增强（旋转、平移、翻转等）。

标准化图像数据。

## classification

#### class
```dark_circles```: Normal，Blue，Brown，Gray，Yellow

```Eye_bags```: Normal，Mild，Moderate，Severe，Edema

```Lips```: Normal，Pale，Red，Dark，Purple

## env
```
conda activate facR
```

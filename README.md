# vip-cup

Code snippet to download processed and compressed dataset

```python
! wget "https://drive.google.com/uc?export=download&confirm=s5vl&id=1-4bkZ0NDrYMAdaLlyWvVjCyCq1by0gy9" -c -O "pro_dataset.zip"
! unzip pro_dataset.zip
import torchvision
data_dir = "/content/data_pro"
dataloader = torchvision.datasets.ImageFolder(data_dir)
```

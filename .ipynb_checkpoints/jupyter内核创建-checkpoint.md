# Step 1
```
conda create -n d2l python=3.9
#XXX是指自己为内核环境起的名字，Python版本编号自己设定。
```
# Step2
```
conda activate d2l
#激活该环境。退出可使用conda deactivate XXX。
```
# Step3
```
conda install ipykernel
#在该环境下安装内核。
```
# Step4
```
python -m ipykernel install --user --name d2l --display-name "env-d2l"
#为内核创建一个放置的空间。d2l是在conda中创建的环境名，后一个‘env-d2l'则是该环境在jupyter中对应的内核名字。
#这一步非常重要！
```


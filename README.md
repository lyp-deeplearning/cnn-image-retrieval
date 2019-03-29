# cnn-image-retrieval
used by caffe 
## 1、算法来自于寒小阳博客  
blob:https://blog.csdn.net/han_xiaoyang/article/details/50856583 
## 2、使用流程
（1）运行exact_features.py函数  
用该函数来提取特征有128维的和4096维的  
（2）运行find_ann_picture.py函数  
用该函数来查询最相近的图片  
可能遇到的bug:  
(1)python3里面的使用的pickle格式  
(2)如果使用lshash的库，注意python3下lshash库的格式

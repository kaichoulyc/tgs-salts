# AlbuNet for TGS salts Identification

Albunet is moification of standart unet [arXiv paper](https://arxiv.org/abs/1801.05746) made by [Vladimir Iglovikov, Alexey Shvets](https://github.com/ternaus/TernausNet)

![UNet11](https://habrastorage.org/webt/hu/ji/ir/hujiirvpgpf7eswq88h_x7ahliw.png)

This net was used by me for TGS salts Identification chalange and showed quite good results even without augmentations and long learning.

For evaluation was used IoU. [Score](https://www.kaggle.com/c/tgs-salt-identification-challenge/leaderboard): 0.69 on public and 0.72 on private 
![IoU](https://www.pyimagesearch.com/wp-content/uploads/2016/09/iou_equation.png)

# Reps used for this project:

https://github.com/ternaus/TernausNet

https://github.com/bermanmaxim/LovaszSoftmax

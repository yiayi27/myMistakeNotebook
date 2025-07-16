# myMistakeNotebook
This is my mistake notebook, used to record the errors I make while reading papers and conducting experiments. I hope it can remind me, and if it can also help anyone who reads it, I would be even happier.

1.如果你是擅用AI做实验的人，请务必要时刻保存best版本，否则后期改来改去很难回滚
2.在A文件中调用B文件的，请确保你想要的变量可以不同名，务必要对齐
3.如果在做实验的途中，尝试了一些模块文件，后面发现表现不好，要及时删除（包括文件和注释的代码段）
4.请尽量不要在同一个模型文件里面训练两个不同的模型，请加以备份再做修改（超级重要）
  虽然模块是不同的，但是调参的时候会调到相同的超参数，请一定不要用同一个文件夹
5.当前实验的log:
减少Learning Rate 从0.003到0.0003  0.93953/0.04942  ->  0.94884/0.04675  保留
增加Learning Rate 从0.0003到0.001  ->  0.96279/0.04635  保留                 
将lossMask置为False  ->  0.97209/0.04821  保留
增加Learning Rate 从0.001到0.0012  ->  0.97674/0.04486
增大Learning Rate 从0.0012到0.0016  -> 0.98605/0.04306

6.寻找论文的tips

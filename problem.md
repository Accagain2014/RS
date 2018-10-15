## Q1: ODG(online gradient descent)或者SDG(stochastic gradient descent)和FTRL本质区别
> 解的稀疏性，简单的在线梯度下降很难产生真正稀疏的解，稀疏性在机器学习中是很看重的事情，尤其我们做工程应用，
<br> 稀疏的特征会大大减少predict时的内存和复杂度。这一点其实很容易理解，说白了，即便加入L1范数，
<br> 因为是浮点运算，训练出的w向量也很难出现绝对的零。
- ODG/SDG的问题：
    - 1）精度低；2）收敛慢；3）几乎得不到稀疏解。
- 其中对online learning最重要的问题是SGD很难得到需要的正则化设计的解，特别是几乎得不到稀疏解。    
- 解释：https://zhuanlan.zhihu.com/p/20447450


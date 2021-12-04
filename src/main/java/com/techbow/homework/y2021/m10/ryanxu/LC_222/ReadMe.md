### 解题思路：
根据题意可知，complete binary tree每一层所有node都尽可能的靠左，并且只有当前层满了才可以填下一层。综上
可以分为两种情况:
1. root左子树和右子树高度相等，这时左子树除了叶子结点以外一定都有两个子结点，所以只需要计算右子树有多少个
结点即可。
2. root左子树比右子树高一层，这时右子树除叶子结点意外一定都有两个子结点，所以只需要计算左子树有多少个结点
即可。
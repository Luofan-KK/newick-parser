# newick-parser
parse newick format tree by C++ source file
## Input:
newick format tree
## Output:
size of tree
label
table of each node's father, distance to father, and bother
## Advantages:
* Open source C ++ newick parser
* Just need C++ 11 compiler (change unordered_map to map, it will need nothing), no other denpendedce
* Simple algorithm means you can edit it whatever you like
# newick解码器
## 输入
newick格式的进化树
## 输出
树所有结点数
每个结点对应的ID
每个结点的父亲、到父亲的进化距离、兄弟 数据表
## 优势
* 开源的C++ newick解析器，而不是使用动态链接库
* 只需要一个支持C++ 11的编译器（如果将其unordered_map 也就是哈希表改成map，即二叉树，那么几乎任何一个编译器都可以使用）
* 因为代码足够简单，所以你可以自行更改

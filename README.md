# AVLtree
一个自平衡二叉树  
当插入和删除节点时，会自动进行平衡操作的二叉树  
插入节点时需要提供一个key值和一个卫星数据data值，其中data结构需要定义复制构造函数，最好有移动构造函数
提供前序、中序、后序、层级遍历功能，遍历结果以一个vector<pair<int,Elementtype>>容器返回  
提供一个empty函数，测试树是否为空  
提供一个get_data函数，接受一个key值，返回一个data的引用  
提供一个get_hetight函数，返回树高

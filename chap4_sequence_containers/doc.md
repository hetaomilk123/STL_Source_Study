30.经典代码：
```c++
size_type num_nodes = num_elements / buffer_size() + 1;
// 以下令nstart，nfinish指向map所拥有之全部节点大最中央区段
map_pointer nstart = map + (map_size - num_nodes);
map_pointer nfinish = nstart + num_nodes - 1;

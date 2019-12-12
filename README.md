# grm

1.桥接了go结构，redis key-value值，mysql表数据的映射处理，以及对数据的crud处理。

2.go结构和redis key-value值为同步处理，mysql永久存储为异步处理。

3.每个字段处理能允许一次脏数据，即redis同步处理某个字段后，需等待异步mysql落地才能再次处理该字段。


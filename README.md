# 物体识别（奶酪）
测试模型根据<a href="https://www.baidu.com" target="_blank">Python 数据科学入门教程：TensorFlow 目标检测</a>生成
所以是用于测试奶酪（应该是吧）

由于原项目创建比较早，一些东西已经过时，所以Fork下重新进行编译，并替换成自己的模型进行测试

如果要替换模型，可直接替换`assets`目录下的`model.db`，模型可根据上面的博客进行生成，对应的目录在`\object_detection\mac_n_cheese_inference_graph\frozen_inference_graph.pb`

同时，`labels.txt`里也要替换成对应的标签，注意第一个`unlabeled`请不要删除！

到此应该就可以运行啦~！

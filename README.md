# dynamic_bp_network_regression
'''
建立一个网络结构可变的BP神经网络通用代码：

在训练时各个参数的意义：
hidden_floors_num：隐藏层的个数
every_hidden_floor_num：每层隐藏层的神经元个数
learning_rate：学习速率
activation：激活函数
regularization：正则化方式
regularization_rate：正则化比率
total_step：总的训练次数
train_data_path：训练数据路径
model_save_path：模型保存路径

利用训练好的模型对验证集进行验证时各个参数的意义：
model_save_path：模型保存路径
validate_data_path：验证集路径
precision：精度

利用训练好的模型进行预测时各个参数的意义：
model_save_path：模型的保存路径
predict_data_path：预测数据路径
predict_result_save_path：预测结果保存路径
'''


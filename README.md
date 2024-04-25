# -
基于大语言模型的智能诊断系统

开源代码与组件使用情况说明：
        操作系统 Ubuntu；
        深度学习库Pytorch；
        编译环境 Python；
        模型加载 Transformers；
        自然语言处理 Datasets；
        Gradio加载模型Webui；
        Wandb进行模型训练参数可视化；
        训练框架LLaMA Factory。

作品安装说明：
        1，复制代码到文件夹中
        2，创建conda虚拟环境：conda create -n xunyiwenyao python=3.10
        3，终端输入pip install -e .[metrics]
        4，输入CUDA_VISIBLE_DEVICES=0 GRADIO_SERVER_PORT=7860  python src/train_web.py

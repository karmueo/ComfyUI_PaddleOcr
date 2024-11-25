# ComfyUI_PaddleOcr
本节点主要是基于PaddleOcr模型，进行Ocr检测和识别，并输出图片、字符串、JSON信息。
![image](https://github.com/karmueo/ComfyUI_PaddleOcr/blob/main/doc/ocr.png)


# 节点
|名称                          |描述                             |
|------------------------------|--------------------------------|
|下载模型                       |自动下载并加载PaaleOcr的三个模型   |
|OCR识别                       |输入图片和模型，进行OCR推理 |

# 需要安装的依赖
本节点调用的是官方提供的python包,你还需要安装下面的依赖

```
pip install -r requirements.txt
```
# 实验一：NLP 前置技术——Python 环境搭建

自然语言处理课程实验一成果：Python 环境检查、中文与英文分词及词频统计。

## 实验内容

- 检查 Python 和相关依赖库的版本。
- 使用 jieba 进行中文分词，并使用 Counter 统计词频。
- 检查、下载 NLTK 的 punkt 和 punkt_tab 资源，完成英文分词。
- 对分词结果、标点保留和词频统计进行分析。

## 文件说明

| 文件 | 内容 |
|---|---|
| [实验 notebook](./nlp_environment_tokenization.ipynb) | 原始实验代码及已保存的运行输出 |
| [实验报告 PDF](./nlp_environment_tokenization_report.pdf) | 排版完成的中文实验报告 |
| [报告 LaTeX 源文件](./nlp_environment_tokenization_report.tex) | 报告源文件，使用 XeLaTeX 编译 |
| [images](./images/) | 报告使用的五张实验截图 |

资源下载截图中的姓名、学号、文件标题及该截图的本地用户名已遮盖，实验代码和下载结果保留。

## 实验环境记录

以下版本取自 notebook 已保存的实际输出。

| 软件或依赖 | 版本 |
|---|---|
| Python（Anaconda） | 3.14.6 |
| NumPy | 2.4.6 |
| pandas | 3.0.3 |
| scikit-learn | 1.9.0 |
| jieba | 0.42.1 |
| NLTK | 3.10.0 |

Notebook 元数据记录的内核显示名称为 `Python (NLP)`，内核标识为 `nlp`。Matplotlib 已在环境检查代码中导入，其版本未记录。

## 查看与运行

直接打开 PDF 可阅读完整报告；在 Jupyter 中打开 `.ipynb` 可查看代码及原始输出。

Notebook 保留原来的单元顺序、执行编号和运行结果。重新运行时，先检查环境，再运行 NLTK 资源下载单元，随后运行中文分词与英文分词单元。`pip install jieba` 单元未保存执行编号或输出，不作为安装成功记录。

编译报告时，将 `.tex` 与 `images` 文件夹保持在同一层。源文件使用 Windows 的宋体、黑体和 Times New Roman 字体。

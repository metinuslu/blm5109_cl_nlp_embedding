# Usage of Some Embedding Algorithms (Text to Embedding) and Ensemble Classification for BLM5109 Collective Learning Course at YTU

## Project Details
> **Description:** Usage of Some Embedding Algorithms (Text to Embedding) and Ensemble Classification (SVM, RF, MLP) on Text Datasets & More Details: KolektifOgrenme_HW2_2024Guz.pdf  
> **Course Name:** BLM5109 - Collective Learning  
> **Course Url:** http://bologna.yildiz.edu.tr/index.php?r=course/view&id=6047&aid=3  
> **Course Page:** https://sites.google.com/view/mfatihamasyali/kolektif-%C3%B6%C4%9Frenme  

## Installation
**Step-1:** Create Env. 
```
conda create --name "py_env_312" python=3.12  
conda activate py_env_312  
python -V
```
**Step-2:** Install Libraries & Frameworks
```
# https://jupyter.org/install
pip install jupyterlab

# https://www.tensorflow.org/install
pip install tensorflow

# https://pytorch.org/
pip install torch torchvision torchaudio

```

**Step-3:** Start Jupyter IDE
```
# Start Jupyter Lab / Notebook
jupyter lab
jupyter notebook
```

## Datasets
    - Turkish Product Reviews: https://huggingface.co/datasets/fthbrmnby/turkish_product_reviews
    - Turkish News: https://huggingface.co/datasets/denizzhansahin/Turkish_News-2024?row=0

## Preprocess & Modelling
    - Embedding Models
      - sentence-transformers/all-MiniLM-L12-v2
      - jinaai/jina-embeddings-v3
      - intfloat/multilingual-e5-large-instruct
      - BAAI/bge-m3
      - thenlper/gte-large

    - Models
      - Support Vector Machine (SVM)  
      - Random Forest (RF)
      - Multi Layer Perceptron (MLP)

    - Turkish Product Reviews Dataset
      - Class Type: Binary Class (2) 
      - Models : 3 ML Algorithms
      - Preprocess & Modelling: GridSearch, KFold Cross Validation
      - Code: ProductReview_PreProcess&Embedding.ipynb & ProductReview_Modelling.ipynb

    - Turkish News Dataset
      - Class Type: Multi Class (5) 
      - Models: 3 ML Algorithms
      - Preprocess & Modelling: RandomSearch, KFold Cross Validation
      - Code: News_PreProcess&Embedding_v3.ipynb & News_Modelling-v2.ipynb

## Contact
    - Ahmed Ugur - 23501027  
    - Metin Uslu - 235B7014
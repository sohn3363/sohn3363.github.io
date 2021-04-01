---
layout: default
title: Deep Learning
nav_order: 1
---

# Deep Learning

The docs should have an index page.

## 1. MLP(Multi-Layer Perceptron)


```yml
title: Read The Docs Jekyll Theme
description: Port of the Read the Docs theme to Jekyll to use with GitHub Pages.
```

## 2. CNN(Convolutional Neural Networks)

```yml
# Specific to this theme
site_author: Carlos Pereira Atencio
repo_url: 'https://github.com/carlosperate/jekyll-theme-rtd'
edit_on_github: true
github_docs_folder: true
logo: 'https://your.url/image.png'
site_favicon: 'https://your.url/here.ico'
sticky_navigation: true
prev_next_buttons_location: None
prev_next_buttons_location: top
prev_next_buttons_location: bottom
prev_next_buttons_location: both
search_enabled: true
google_analytics: UA-XXXXX-Y
google_analytics_anonymize_ip: true
# The highlight.js library provides 79 different colours for their syntax highlighting. The default is github-gist.
hljs_style: github-gist
```

## 3. RNN(Recurrent Neural Networks)

---
## 4. Multi-GPU(Data Parallel)  
딥러닝에서 Neural Network는 기본적으로 Matrix 연산을 하기 때문에 CPU 환경보다 GPU 환경에서 학습하는 것이 효율적이다. 또한, 학습과정에서 batch_size는 학습 performance에 영향을 미치고 고품질, 대용량의 데이터를 학습하기 위한 Computing resource는 한정적이기 때문에 단일 GPU보다 여러대의 GPU를 병렬연결하여 하나의 모델을 학습하는 Multi-GPU 방법을 사용하고 있다. 
### 1) Pytorch DataParallel  
```python
print('hello')
```
### 2) Pytorch Custom DataParallel  
```python
print('bye')
```
---

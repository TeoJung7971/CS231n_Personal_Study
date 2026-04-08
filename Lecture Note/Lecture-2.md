# Stanford CS231N Deep Learning for Computer Vision | Spring 2025 | Lecture 2: Image Classification with Linear Classifiers

> Link: [Lecture Video](https://youtu.be/pdqofxJeBN8?si=bDjuYjE54yVT-zPl)
> Slide: [Slide](https://cs231n.stanford.edu/slides/2025/lecture_2.pdf)

---

## Syllabus

![1775572829562](image/Lecture-2/1775572829562.png)

## Image Classification Task

### Image Classification: Core task of CV

- **What to do?**
  - image -> label (one of the possible labels)
  
- **Problem**
  - Sementic Gap
    - 사람이 보는(파악하는) 이미지 vs 컴퓨터(기계)가 인식하는 이미지
    - 시각적 이미지 vs 행렬(a tensor of integers)
  
- **Challenges**
  - Illumination(조명, 광원)
  - Background Clutter(어수선한 배경)
  - Occlusion(가려짐)
  - Deformation(변형)
  - Intraclass Variation(계급(집합) 내 다양성)
  - Context(맥락)
  - etc...

### An Image Classifier

```python
def classify_image(image):
  # Something in Here
  return class_label
```

- **Problem**
  - 정렬(Sorting)과 같은 문제와 달리, hard-code로써 이미지의 class를 분류하는 algorithm(or the steps)을 구축하는 분명한(obvious) 방법은 없음

- **Efforts?**
  - 그럼에도 불구하고, (DL을 통한 접근 이전의) hard-code algorithms을 기반으로 한 몇 시도들이 존재
    - Edge Detecting
      - 
    - 

## Data Driven Approaches to Image Classification

### K-nearest Neighbor

### Linear Classifier

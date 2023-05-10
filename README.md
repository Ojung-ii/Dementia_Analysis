# Dementia_Analysis

**INDEX**

---
1. [**프로젝트 개요**](#1-프로젝트-개요)

    1.1 [**주제**](#1.1-주제)


    1.2 [**주제 선정의 배경**](#1.2-주제-선정의-배경)

    1.3 [**본 프로젝트의 활용 방안 제시**](#1.3-본-프로젝트의-활용-방안-제시)

2. [**프로젝트 팀 구성 및 역할**](#2.-프로젝트-팀-구성-및-역할)


3. [**프로젝트 수행 및 절차 및 방법**](#3.프로젝트-수행-및-절차-및-방법)
---

## 1. 프로젝트 개요 <a name="1-프로젝트-개요"></a>

### 1-1. **주제** <a name="1.1-주제"></a>




---
![노인 아들 치매 사진](https://github.com/yonghyeun/Dementia_Analysis/assets/123540354/7a6244d2-e169-4f2b-9a07-098a7f23bfde)



### **고령화 시대의 의료 불균형 해소를 위한 치매 진단 파이프라인 구축**


 퇴행성 질환인 치매 관련 AI 기술의 필요성을 탐색하고 비정형, 정형 데이터를 통해 치매의 위험 인자를 탐색, 예측, 판단 할 수 있는 모델을 개발한다.

- **라이프로그 데이터** : 웨어러블 기기를 통해 수집한 정형 데이터로 치매 위험 인자를 판별하고 M.L / D.L 모델을 통해 경도 인지 장애 단계를 조기에 예측한다.
- **비정형 데이터(MRI)** : 영상 이미지 데이터를 통해 치매를 판단한다.

### 1-2. **주제 선정의 배경** <a name="1.2-주제-선정의-배경"></a>

---

### 👵🏼  치매 유병률 증가와 가속화되는 **의료 불균형**
- **고령화** : 고령화에 따른 치매 유병률은 기하급수적으로 늘어나는데, 의료 불균형은 가속화 되고 있다. 의료인력 부족 문제가 지방에서는 이미 발생하고 있으며, 이런 추세라면 의료 공백 문제가 더욱 심화될 것이다.
- **의료산업** : 의료 인력을 도울 수 있고 효율성을 향상시키는 'AI(인공지능)'를 활용한 의료기술 산업은 성장성이 높고 낮음을 떠나서 '반드시 성장해야 하는 분야'라고 생각한다. 실제로 [구글](https://www.aitimes.com/news/articleView.html?idxno=149965)이나 [애플, 아마존](https://www.chosun.com/economy/science/2023/02/16/3BEKAY3DY5DUZM3BNF7INVAGWI/)과 같은 글로벌 선도기업들도 관련 분야에 엄청난 투자를 쏟고 있다.

<img width="707" alt="치매 환자 유병률 및 빈도수" src="https://github.com/yonghyeun/Dementia_Analysis/assets/123540354/30ea02da-9082-4cdb-97b4-00b1b2b996ca">

**출처** : 보건복지부지정 노인성치매 일산연구센터
    
    [구글, 의료전문 LLM '메드-PaLM' 공개...헬스케어 AI 소개](https://www.aitimes.com/news/articleView.html?idxno=149965)
    
    **구글**에서 의료 전문 LLM(대규모 언어 모델)을 공개
    
    [애플, 건강 모니터링 서비스… 아마존, 5조 들여 원격의료 기업 인수](https://www.chosun.com/economy/science/2023/02/16/3BEKAY3DY5DUZM3BNF7INVAGWI/)
    
    **애플**: 아이폰을 통한 개인 건강 기록과 애플워치를 통해 수집한 데이터를 바탕으로 건강 모니터링 서비스를 제공
    **아마존**: 원격의료 기업 원메디컬 인수 
    

### 🏥  **의료분야에서의 AI모델 활용?**

- **조기진단 및 예측** : 알츠하이머와 같은 질병은 사실 MRI 상으로 판별하기 쉽다. 하지만 치료법이 없는 이런 질병은 발병 후 발견하면 큰 의미가 없다. 조기에 예측하는 것이 무엇보다 중요하다.
    
<img width="782" alt="치매 조기진단의 중요성" src="https://github.com/yonghyeun/Dementia_Analysis/assets/123540354/ae4d6365-aac5-4a04-941b-9e635db0b97e">

    
    ["AI 활용한 치매치료 기술, 고령화 시대에 가장 필요한 솔루션"](https://www.pharmnews.com/news/articleView.html?idxno=220533)
    
- **정확도, 시간 단축** : MRI, PET 등의 분석을 통한 질병 유무 판별은 많은 시간이 소요되는 과정이다. M.L / D.L 모델은 이런 과정을 단축하고 정확도 면에서도 더 우수하다.

### 1-3. 본 프로젝트의 활용 방안 제시 <a name="1.3-본-프로젝트의-활용-방안-제시"></a>

---

- 라이프 로그 데이터를 통해 치매 예측 모델 개발
- 라이프 로그 데이터로 예측 후 직접 만든 MRI 분류 모델로 검증


💡 **효용성**

1.  병원 밖에서 수집 가능한 데이터를 가지고 진단 모델을 만듦으로써 지역 사회에서도 의료 서비스를 이용 할 수 있다.
2.  생활하며 수집되는 데이터를 활용한 모델로써, 더욱 많은 데이터를 쉽게 수집할 수 있으며 금전적인 부담이 없다.  
3.  AI 기술을 활용해 부족한 영상의학과 및 신경과 등 불균형한 의료 인력에서 오는 부담을 줄일 수 있다.

**제한점** 

1.  치매란 인지 기능 및 다양한 의학적 근거를 통해 진단되어야 하기에 완벽한 조기 진단을 보기 위해선 다양한 전문 의료 인력이 필요하다.
2.  라이프로그 데이터에서는 치매 환자의 표본이 부족한 문제점을 가지고 있으며 치매의 증상은 생활 수준의 변화 뿐이 아니라 다양한 변화를 가지고 오기에 다양한 변수를 수집해 모델링하여 더욱 정확도 높은 예측 결과를 제공해야 한다.
3.  웨어러블 기기의 보편화가 이루어지지 않는다면 조기진단 모델 적용이 어렵다.
4.  신뢰도가 높은 웨어러블 기기를 활용해야 하며, 수집 시 사용한 웨어러블 기기의 신뢰도에 따라 모델링의 결과가 달라질 수 있다.

## 2. 프로젝트 팀 구성 및 역할<a name='2.-프로젝트-팀-구성-및-역할'></a>

| 이름 | 역할 | Github |
| --- | --- | --- |
| 김민기 | 라이프로그 데이터 및 이미지 데이터 분석 결과를 활용한 대시보드 제작 |[@BDDKID](https://github.com/BDDKID)|
| 최용현 | 라이프로그 데이터 분석 및 머신러닝 및 딥러닝을 활용한 예측 모델 개발 |[@yonghyeun](https://github.com/yonghyeun)|
| 김지민 | 두개골 없앤 MRI를 학습한 모델에 OASIS2데이터 적용  |[@kjmn1105](https://github.com/kjmn1105)  |
| 김희묵 | CANNY로 MR외곽선을 학습한 모델에 OASIS2데이터 적용  |[@2mook2](https://github.com/2mook2)|
| 오정현 | 데이터 증강을 통해 일반화한 학습한 모델에 OASIS2데이터 적용  |[@Ojung-ii](https://github.com/Ojung-ii)|
| 최유현 | OASIS-2 demographics 데이터로 치매 예측에 유의미한 변수 탐색  |[@yu-hyun2](https://github.com/yu-hyun2)


## 3. 프로젝트 수행 및 절차 및 방법<a name='3.프로젝트-수행-및-절차-및-방법'></a>
### 라이프로그 데이터 모델링
| LogisticRegression | 로지스틱 회귀분석은 데이터 집합의 관측된 개별 결과가 양성 또는 음성인 두 가지 결과 중 하나일 때, 독립 변수와 종속 변수 간의 관계를 모델링하는 데 사용됩니다. |
| --- | --- |
| DecisionTreeClassifier | 의사결정나무 분류기는 입력 변수에 대한 결정 규칙을 학습하고, 이를 사용하여 관측 결과의 클래스를 예측하는 데 사용됩니다. |
| SVC | SVM은 고차원 공간에서 선형 및 비선형 분류, 회귀 및 이상치 탐지 문제를 해결하는 데 사용되는 강력한 분류 알고리즘입니다. |
| KNeighborsClassifier | KNN 분류기는 새로운 관측값의 클래스를 예측할 때 가장 가까운 이웃 데이터의 클래스를 사용하는 분류 알고리즘입니다. |
| RandomForestClassifier | 랜덤 포레스트는 여러 개의 의사결정나무를 생성하고 그들의 예측을 조합하여 보다 정확한 예측을 수행하는 데 사용됩니다. |
| XGBClassifier | XGBoost는 Gradient Boosting 알고리즘을 기반으로 하며, 빠른 속도와 높은 예측 정확도를 제공하는 데 사용됩니다. |
| LGBMClassifier | LightGBM은 Gradient Boosting 알고리즘을 기반으로 하며, 대규모 데이터 집합에서 빠른 학습 및 높은 예측 정확도를 제공하는 데 사용됩니다. |
| Catboost | Catboost는 Gradient Boosting 알고리즘을 기반으로 하며, 범주형 변수를 처리하는 데 있어서 다른 Gradient Boosting 라이브러리와 비교하여 보다 뛰어난 예측 성능을 제공하는 데 사용됩니다. |
| DNN | Deep Neural Network는 여러 층으로 구성된 인공 신경망 모델로, 이미지, 음성, 텍스트 등 다양한 데이터 유형의 예측 및 분류에 사용됩니다. |

### MRI 이미지 데이터 
| CNN | CNN은 Convolutional Neural Network의 약자로, 이미지와 같은 고차원 데이터를 처리하기 위한 인공 신경망의 한 종류입니다. 이미지 분류, 객체 검출, 분할 등 다양한 이미지 처리 작업에서 사용됩니다. |
| --- | --- |
| Canny | Canny Edge Detection은 이미지에서 에지(Edge)를 검출하는 알고리즘 중 하나입니다. 이미지의 밝기 변화가 큰 지점을 찾아서 에지로 인식합니다. |
| Contour | Contour는 이미지에서 최외곽의 경계선 위치를 검출하고, 그 위에 검은색 선을 덮어 씌워 두개골을 지우는 방식입니다.  |
| Augmentation | Augmentation은 데이터 증강 기술로, 기존 데이터에 다양한 변형을 적용하여 데이터셋을 보강합니다. 예를 들어 이미지에서는 회전, 크기 조정, 반전 등의 변형을 적용하여 데이터를 다양하게 만들어 모델의 성능을 향상시킵니다. |

# AIFFEL_DLThon_1
- 아이펠캠퍼스 리서치 온라인 10기 DLThon 1조 repository
- https://www.kaggle.com/competitions/aiffel-dl-thon-online-10

### 발표자료
- https://docs.google.com/presentation/d/1LBH7XkCe1M8twiu_pcHzwiwn241L9kJ7hcTDStycQws/edit#slide=id.p
## Member
|팀장|팀원|팀원|팀원|  
|:----:|:---:|:-----:|:---:|  
|황동주|김용석|김하영|박세희|  

![image](https://github.com/user-attachments/assets/dfdf6de9-e3d5-4044-bbed-307fd1c7ee7a)

## Overview
- 대화의 성격을 위협 세부 클래스 4개 또는 일반 대화 중 하나로 예측하는 과제  
- 학습 데이터는 '협박', '갈취', '직장 내 괴롭힘', '기타 괴롭힘' 등 4개 클래스 각 약 1천 개로 구성  
- 테스트 데이터는 '협박', '갈취', '직장 내 괴롭힘', '기타 괴롭힘', '일반 대화' 등 5개 클래스 각 1백여 개로 구성
  
train data에는 없지만, test data는 일반 대화 클래스가 존재합니다.
5개 문장을 분류할 수 있게 train data에 일반 대화 데이터셋을 추가합니다.

일반대화는 합성데이터로 구성합니다.  
다양한 프롬프트로 문장을 생성하고, 이를 학습에 활용합니다.  
[일반대화 클래스]를 제외한 데이터의 추가나 외부 데이터 사용 불가(단, Augmentation은 가능)  
Pre-trained model은 공개된 모델에 한하여 사용 가능(재현성을 위함)  
학습 결과를 확인하며 어떤 일반 대화 데이터셋이 성능을 높이는데 도움을 주는지 비교/기록합니다.  
위 기준에서 벗어나지 않는 범위 내에서 데이터셋의 구성은 자유입니다. 성능을 비교/기록해보세요 :)  
일반대화 데이터셋은 여러 방식으로 구할 수 있습니다. 어떤 경로를 통해 얻은 데이터셋의 성능이 좋은지 비교/기록합니다.  
합성데이터 생성 및 활용, 기 확보된 데이터 활용(추가실험)  
실험 결과를 Ablation study형식으로 기록합니다  
  
## Basic Information
 
|클래스|Class No.|# Training|# Test |
|:----:|:------:|:------:|:------------:|
|협박 |00| 896    | 100   |
|갈취  |01|981     | 100 |
|직장 내 괴롭힘  |02|979     |100|
|기타 괴롭힘 |03|1,094      |100|
|일반 |04| - |100|  

## 프로젝트 일정    
| 일정 | 12/05 | 12/06 | 12/09 | 12/10 |
| --- | --- | --- | --- | --- |
| 오전 | 팀빌딩 및 프로젝트 안내 | 프로젝트 진행 | 프로젝트 진행 | 발표 준비 |
| 오후 | 프로젝트 진행 | 프로젝트 진행 | 프로젝트 진행 | 발표 |

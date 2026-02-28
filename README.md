# ♻️ CNN-Recycle-Classification (재활용품 이진 분류 모델)  
  
> 🏆 **2023 한국정보기술학회 하계종합학술대회 금상 수상작** <br>  
> **상세 트러블슈팅 및 데이터 전처리 과정은 [https://www.notion.so/2e697446a87a806fb109c8b51f35af2c?source=copy_link]에서 확인하실 수 있습니다.**  
  
## 1. Project Overview  
COVID-19 이후 급증한 무분별한 쓰레기 배출 문제를 해결하기 위해, 폐기물 이미지를 CNN 알고리즘을 통해 **'재활용품(Recyclable)'**과 **'일반 쓰레기(Trash)'**로 자동 분류해 주는 이진 분류(Binary Classification) AI 모델입니다.  
  
## 2. Tech Stack  
* **Language**: `Python`  
* **AI Framework**: `TensorFlow (Keras)`  
* **Data Processing**: `OpenCV`, `NumPy`, `ImageDataGenerator`  
  
## 3. Key Achievements & Performance  
* **Test Accuracy**: `95.5%` 달성  
* **Data Augmentation**: 수집 난이도가 높은 '일반 쓰레기' 데이터의 절대적 부족(Imbalance) 현상을 극복하기 위해 `Rescale`, `Shear`, `Horizontal Flip` 등의 증강 기법을 적용하여 모델의 범용성 확보.  
* **Model Optimization**: 과적합(Overfitting) 방지를 위해 Dropout(0.25) 적용 및 망의 깊이를 조절한 커스텀 CNN 아키텍처 설계.  
  
## 4. Repository Structure  
```text  
📦 CNN-Recycle-Classification  
 ┣ 📜 trash_binary.ipynb   # 데이터 전처리, CNN 모델링 및 평가가 포함된 메인 주피터 노트북  
 ┗ 📜 README.md  

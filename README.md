# 2024-NC2-M17-MachineLearning

## 🎥 Youtube Link
(추후 만들어진 유튜브 링크 추가)

## 💡 About Augmented Reality

인공지능(AI)의 한 분야인 머신 러닝(ML)은, 데이터 안의 패턴과 구조를 분석해 인간의 도움 없이 스스로 학습하고 추론하는 계산 과학입니다. 사용자가 컴퓨터 알고리즘에 많은 양의 데이터를 넣으면, 그 컴퓨터가 스스로 데이터를 바탕으로 결정을 내리며 분석을 진행합니다. 

이 과정에서 수정이 필요한 부분이 발견되면, 알고리즘은 새로운 정보를 통합하여 앞으로 더 나은 의사결정을 할 수 있게 됩니다. 머신 러닝은 인간이 정한 규칙 없이도 독자적인 경험을 쌓아가며 학습합니다.



## 🎯 What we focus on?
Machine Learning에서 Hand Pose를 활용한 모델을 만들고 앱에 적용한다.

- 모델 클래스: 직관적인 포즈, 타이머 사인은 사진 찍는 포즈와 최대한 중복되지 않게
- Create ML 사용: 소수의 퍼센트로 다른 판단이 나오면? training/test 파일 수집 및 적용
- 코드: 타이머가 돌아가고 있을 때 또 포즈를 인식하지 않게, 만든 ML 모델 앱에 활용하기
## 💼 Use Case
> Machine Learning을 이용하여 멀리서도 수월하게 사진을 찍을 수 있게 하자!

## 🖼️ Prototype
App의 컨셉이 카메라 앱인 만큼 디자인 요소가 많지 않았습니다. 최대한 기본 카메라 앱과 비슷하게 하여 익숙한 기본 카메라를 쓰듯 자연스러운 느낌이 나게 하였고, 타이머 사인을 인식했을 때 멀리서도 본인의 사인을 인식했다는 느낌을 주기 위해 소리와 함께 타이머 숫자를 크게 알리듯 하였습니다.

머신러닝을 활용하는 부분입니다. 이때, vision을 사용합니다. setupvision이라는 함수를 만들고 함수 내에서 모델을 불러옵니다. 위 코드는 모델을 불러온 뒤, 인식한 값이 3일 경우에 3초 타이머를 실행하고 사진을 촬영하여 저장하는 부분입니다.

## 🛠️ About Code
카메라 관련 함수의 경우 촬영, 저장, zoom, 전후면 전환, 플래시, 무음을 기준으로 분리하여 제작하였습니다.
머신러닝을 활용 부분에서는 vision을 사용합니다. setupvision() 이라는 함수를 만들고 함수 내에서 모델을 불러옵니다. 위 코드는 모델을 불러온 뒤, 인식한 값이 3일 경우에 3초 타이머를 실행하고 사진을 촬영하여 저장하는 부분입니다.

# Gan
## training strategy
1. 실제 데이터셋을 **미리 살펴보기**
2. **판별기**가 적어도 실제 데이터와 임의의 노이즈를 구별하도록 학습할 수 있을 성능은 지니는지 확인
3. **훈련되지 않은 생성기**가 올바른 형태의 데이터를 만들어내는지 확인
4. 손실이 어떻게 변하는지 시각화
----
**생성기의 loss**는 **생성된 데이터로부터 발생한 판별기의 손실**임.

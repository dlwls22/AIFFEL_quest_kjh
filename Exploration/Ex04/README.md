# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김종환
- 리뷰어 : 진수민


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 인물, 고양이, 크로마키 배경에 대해서 실험을 잘 진행함
        - ![image](https://github.com/user-attachments/assets/87a46e3a-aed5-43d1-af80-f9f444306291)
        - ![image](https://github.com/user-attachments/assets/4349f307-8e47-49ab-a7a0-0376255ea751)
        - ![image](https://github.com/user-attachments/assets/a869e5e5-7497-4e1c-af55-be42d8855d9a)
        - segmantation 에러 원인 분석 및 이에 대한 솔루션 제시
        - ![image](https://github.com/user-attachments/assets/36a785b8-b0d8-45a5-853d-88bf68f3409d)
          

- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - label name을 함께 작성하여 디버깅을 쉽게 함
        - ![image](https://github.com/user-attachments/assets/89c20191-60a1-44b8-ac31-380a6657a82c)


        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - segmantation에 대해 에러난 부분에 대해 인덱싱이 되어있음
        - ![image](https://github.com/user-attachments/assets/7001e31e-c323-408f-93b2-0c0ec0a58eab)
        - 에러난 부분에 대해 기록함
        - ![image](https://github.com/user-attachments/assets/3c5ef785-7d2a-489c-82e7-0175c2664500)
        - 사진이 잘린 부분도 segmantation의 오류 문제를 토대로 색분리를 진행하고 분석함
        - ![image](https://github.com/user-attachments/assets/f9c086d2-1288-4d5f-9da0-5ac20cf76c23)
        - ![image](https://github.com/user-attachments/assets/b057ec13-b98e-4a2f-a106-b12bcddcc8f7)



- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 회고 및 오류 서정에 대한 솔루션도 잘 작성되었음.
        - ![image](https://github.com/user-attachments/assets/374a0e4e-b659-46dd-b61c-4ea4f3d7fc0e)


        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 이미지 로드 및 모델 다운로드를 함수화 함 - 반복되는 내용을 함수화 해서 사용.
        - ![image](https://github.com/user-attachments/assets/d1fb80c2-d1f5-4d08-ac10-12a16dfb4229)
        - ![image](https://github.com/user-attachments/assets/77d24fc7-767b-414b-a698-0c6ceb9a4c84)
      



# 회고(참고 링크 및 코드 개선)
```
- 짧은시간 내에 굉장히 다양한 실험과 확장된 내용을 다루어 주셔서 보는 입장에서 많이 배웠습니다!
- 특히 점프를 뛰며 촬영한 사진에 대한 분석을 semantic segmentation mask error와 연관지어 작성한 부분이 인상깊었습니다.
- 실험을 통해 공부를 확장한 것이 보입니다.
```

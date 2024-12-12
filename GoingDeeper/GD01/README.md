# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 김하영
- 리뷰어 : 이창민


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - 모든 결과물이 적절하게 나타나있다.
        - <img width="655" alt="스크린샷 2024-12-12 오후 4 59 48" src="https://github.com/user-attachments/assets/33ccba0c-c935-46ec-82ed-4a3ad725f1d8" />
        - <img width="650" alt="스크린샷 2024-12-12 오후 5 00 13" src="https://github.com/user-attachments/assets/e92a4b8d-5b4b-4b27-b84d-b9293c8bb748" />
        - <img width="720" alt="스크린샷 2024-12-12 오후 5 00 41" src="https://github.com/user-attachments/assets/416569ee-9c26-4164-b2f7-892e4006dbfb" />
        - <img width="720" alt="스크린샷 2024-12-12 오후 5 01 05" src="https://github.com/user-attachments/assets/193dc2f8-cbce-4287-be14-6d2da06712b6" />
        - <img width="548" alt="스크린샷 2024-12-12 오후 5 01 29" src="https://github.com/user-attachments/assets/a1d079a5-368c-4d92-80cd-790b7819bbfb" />
        - <img width="603" alt="스크린샷 2024-12-12 오후 5 01 48" src="https://github.com/user-attachments/assets/1ec8000b-79c0-439f-9b46-2e188ebe9991" />
        






    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 직접 구현한 모델에서 알아보기 쉽도록 적절한 주석처리 진행
        - <img width="642" alt="스크린샷 2024-12-12 오후 5 06 28" src="https://github.com/user-attachments/assets/aa142feb-2502-4cda-bdb4-6f5cfee34225" />


        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 데이터 셋을 불러올 때 발생한 오류를 발견하고 적절하게 대처함
        - <img width="734" alt="스크린샷 2024-12-12 오후 5 05 09" src="https://github.com/user-attachments/assets/ff73d90e-acc6-4a0e-8bb3-6ce277407d35" />

        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 그래프를 보고 적절한 결과를 도출해냄
        - <img width="575" alt="스크린샷 2024-12-12 오후 5 02 47" src="https://github.com/user-attachments/assets/29affc4e-83cd-4c24-a250-a240731aff87" />


        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 모델 구현 시 알아보기 쉽게 주석처리, 줄바꾸기를 사용했고, 블럭과 모델 등 적절하게 모듈화 되어있음.
        - <img width="893" alt="스크린샷 2024-12-12 오후 5 07 44" src="https://github.com/user-attachments/assets/d3070c54-5ccd-46a2-b535-59f44a9b031f" />






# 회고(참고 링크 및 코드 개선)
```
총 두 개의 데이터 셋을 통해 네 모델을 평가했고, 그래프를 통해 결과 분석까지 진행했다.
해당 과정에서 우리가 학습했던 ablation study가 잘 이뤄졌다고 느꼈다.
추가적으로 markdown 사용으로 깔끔하게 구분해서 찾아보기 쉽게 정리한 부분이 좋았다.

```

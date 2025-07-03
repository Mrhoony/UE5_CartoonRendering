# UE5_CartoonRendering
UE5.5 Shader ToyProject<br>
※ 진행중인 프로젝트 ※

### 목차
1. [계기](https://github.com/Mrhoony/UE5_CartoonRendering/tree/main?tab=readme-ov-file#%EA%B3%84%EA%B8%B0)
2. [결론](https://github.com/Mrhoony/UE5_CartoonRendering/tree/main?tab=readme-ov-file#%EA%B2%B0%EB%A1%A0)
3. [결과물](https://github.com/Mrhoony/UE5_CartoonRendering/tree/main?tab=readme-ov-file#%EA%B2%B0%EA%B3%BC%EB%AC%BC)
4. 프리넬 (Fresnel)
5. 뎁스버퍼 (DepthBuffer)
6. 배면법V1 (BackSideV1, 2메쉬+1패스)
7. 배면법V2 (BackSideV2, 1메쉬+1패스)
~~8. 배면법V3 (BackSideV3, 1메쉬+2패스)~~
9. 배면법Final (BackSideFinal, 1메쉬+1패스)
<br>

---
### 계기
[![Image](https://github.com/user-attachments/assets/5b48908a-0470-4fc8-a12c-dce7b92a9e0a)](https://youtu.be/AZ_9ifeR518?si=LJRelBTPW4V4kJvF)<br>
[(Youtube - 3Dでキレイな線を引くために。ギルティギアシリーズのトゥーンライン制御テクニック Part1【アークシステムワークス公式】)](https://youtu.be/AZ_9ifeR518?si=LJRelBTPW4V4kJvF)

회사에서 동료분의 소개로 아크시스템웍스의 길티기어 xrd에서 배면법과 멀티패스를 이용한 아웃라인 기법에 대한 영상을 접하게 되었다.<br>
아웃라인의 선의 두께가 균일하지 않고 마치 "그린듯한" 느낌이 꽤 매력적이어서 시간이 되면 직접 구현해봐야겠다고 생각했다.<br>
영상을 접했을 당시 퇴사를 준비중어서 자연스레 퇴사 후 진행하는 것으로 연결되어 직접 영상에서 알려주지 않은 부분들을 파헤쳐 보았다.<br>
<br>

---
### 결론
엔진 개조가 필수는 아니다.<br>
하지만 게임은 혼자서 만들지 않는다. 이는 길티기어 xrd 역시 마찬가지였을 것이다.<br>
개발 과정에서 불필요한 반복 작업을 줄여서 동료들의 수고로움을 덜어주고 싶은 것이 아니었을까 예상해본다.<br>
<br>

---

### 결과물
![Image](https://github.com/user-attachments/assets/29617f40-9b0f-4ce5-9965-3be4ede73fc4)<br>
모델 교체해서 다시 올릴 예정
<br>

---

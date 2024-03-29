# 아날로그와 디지털

## 아날로그 vs 디지털

- 아날로그 : 연속적
- 디지털 : 불연속적
- 컴퓨터 입장에서는 디지털 데이터가 다루기 쉽다. 압축, 암호화, 병합, 복사, 전송, 저장, 확장에 있어 더 용이하다.

## A/D 변환

### 이미지

RGB 필터 뒤의 미세한 광검출 소자가 빛의 양에 비례하는 양으로 전하를 저장하고 이를 수치로 전환한다.

### 음향

- LP에서 CD로
- 파형을 샘플링하여 부호화
- 압축하여 MP3, AAC 등으로 사용

### 영화

- 정지 영상을 빠르게 보여줬던 아날로그 방식(프레임이 낮아 깜빡거림 flicker이 있었다 -> 영화를 flicks라고 부르던 시절도 있었다)
- 현재는 음향과 영상 요소를 결하하고 동기화한다.

### 텍스트

- 아스키코드
- 유니코드

# 이진수

## 비트

- 디지털 정보를 표현하는 가장 기본적인 방식
- 비트가 n개 있다면 표시할 수 있는 비트 패턴의 개수는 2^n
  
## 바이트

- 8비트
- 모든 최신 컴퓨터의 데이터 처리와 메모리 구성의 단위
- 보통 int(0~255 사이 정수), 7비트 아스키코드 문자 집합(1비트는 부호비트) 등의 데이터를 나타냄
- 비트는 너무 길기 때문에 보통 `십육진수`라는 대안 표기법을 사용한다 : RGB에서도 볼 수 있는 기수이다
- 비트 모임은 **상황에 따라 의미가 달라질 수 있다.** 숫자인지, 문자인지, 다른 수의 일부인지...
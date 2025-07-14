# 과제 6번 회전 발판과 움직이는 장애물 퍼즐 스테이즈
## 필수 과제
### 1. 회전 기능 : Tick 함수에서 AddActorLocalRotation() 을 사용하여 매 프레임 회전 처리
### 2. 이동 기능 : Tick 함수에서 왕복 이동 구현, MoveSpeed, MoveRange, StartLocation 등을 고려해 일정 범위를 벗어나면 이동 방향 전진시키는 로직 구성
### 3. 프레임 독립성 : 이동 / 회전 시 반드시 DeltaTime 을 활용하여 하드웨어 성능 기능에 관계없이 일정한 움직임을 보장

## 도전 과제
### 1. 타이머 활용 : FTimerHandle 과 GetWorld()->GetTimerManager().SetTimer(...) 를 사용해 특정 시간 후 또는 주기적으로 함수 호출, 시간 기반 로직 구현(사라지거나 주기적으로 다른 위치로 이동하는 발판 구현)
### 2. 랜덤 퍼즐 생성 : 동적 스폰(게임 시작 시 SpawnActor를 통해 회전 발판 / 이동 플랫폼을 임의 좌표에 여러 개 배치), 랜덤 속성 부여(회전 / 이동속도, 이동범위, 각도 등을 FMath::RandRange 로 생성하여 매번 다른 퍼즐 코스를 구현)

## 내가 구현한 기능
### 필수 과제 전부 (1~3번)
### 도전 과제 (아직 미구현)

## 내가 사용한 에셋들
### https://www.fab.com/ko/listings/3de203c9-a2b8-474e-abee-40cef47dfe8d
### https://www.fab.com/ko/listings/f2b46d19-096f-410c-a181-de69b0af3221

## 유튜브 동영상
### https://www.youtube.com/watch?v=IO9TEKu_jMA&ab_channel=%EC%BD%94%EB%AA%A8

# 메모장

c++ 버전관리 제외
Saved : 자동저장, 로그, 스크린샷 등등..
Intermediate : 임시 파일 저장
Build : 패키징 하면 생기는거
.vs : vs 관련..
.sln : 협업할 때 없어도 될 것

----

- UE_LOG : 언리얼 로그 함수
- GetOwner() : 이 액터를 소유한 액터를 반환.
- GetOwner()->GetName() : 액터의 이름을 반환.
- GetOwner()->GetTranform().GetLocation() : 액터의 Location을 반환. (위치값)
- UWorld = GetWorld() : 현재 월드 반환.
- GetWorld()->GetTimeSeconds() : 게임이 시작된 후 시간(초단위)를 반환.

----

* FVector : 벡터
* FRotator : 회전

----

* float -> fstring
FString::SanitizeFloat(float변수);

----

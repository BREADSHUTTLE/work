# 메모장


*** 프로젝트 폴더 : _WORK
*** C++ 클래스 : work




---------------------

*c++ 버전관리 제외
- Saved : 자동저장, 로그, 스크린샷 등등..
- Intermediate : 임시 파일 저장
- Build : 패키징 하면 생기는거
- .vs : vs 관련..
- .sln : 협업할 때 없어도 될 것

----

- UE_LOG : 언리얼 로그 함수
- GetOwner() : 이 액터를 소유한 액터를 반환.
- GetOwner()->GetName() : 액터의 이름을 반환.
- GetOwner()->GetTranform().GetLocation() : 액터의 Location을 반환. (위치값)
- UWorld = GetWorld() : 현재 월드 반환.
- GetWorld()->GetTimeSeconds() : 게임이 시작된 후 시간(초단위)를 반환.

----

* FVector : 벡터
* FRotator : 회전 (pitch : y / yam : z / roll : x)

----

* float -> fstring
FString::SanitizeFloat(float변수);

----

* 위젯 생성자
- NativeOnInitialized() : 생성자 함수
- 버튼 델리게이트 : OnClicked.AddDynamic(onwer, callback)

----

* 위젯에서 계층구조를 쌓을 때, 유의사항.
- 계층 구조를 쌓는 것은 유니티와 비슷하지만, 자식을 가지는 갯수가 위젯마다 다르다. (이것 때문에 계층구조가 안만들어지는 불상사를 줄여보자.)
- ![image](https://user-images.githubusercontent.com/25288572/128043945-e00f7702-ba00-40a7-b410-4960e2aa8d0e.png)
- 출처 : https://www.slideshare.net/honggijoe/ui-4-umg-1

----

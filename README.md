# GhostSurviver
### 🎬 이미지를 누르면 시연 영상으로 이동합니다.
[![image](https://github.com/DoroNyong/GhostSurviver/assets/62960758/d1660031-c8c2-46ad-b64d-d9573391937c)](https://youtu.be/urQCWKbKHQQ?si=70AaaC2lUQ_HzFX9)
## 🖥️ 장르 : TPS 생존 게임 (싱글 플레이)
사방에서 몰려드는 유령을 총으로 쏘면서 버티는 3D TPS 게임입니다.

## ⏱️ 개발 기간
- 24.01.31 - 24.02.06

## 🧑 제작 인원
- 장현교 : 1인 개발 입니다.

## ⚙️ 개발 환경
- **Framework** : .Net 2.0
- **Language** : C#
- **Engine** : Unity 2022.3.2f1
- **IDE** : Visual Studio 2022

## 📌 주요 기능
- 캐릭터, 카메라
  - 오일러각과 쿼터니언을 사용해 자연스럽게 움직이고 회전시켰습니다.


- 적 개체
  - 상속을 활용해 여러 적 개체를 하나로 묶어서 관리했습니다.
  - 오브젝트 풀링을 사용해 적 개체를 관리했습니다.
  - 투명도는 머티리얼 인스턴싱과 코루틴을 사용해 등장과 퇴장시 투명도를 조절했습니다.
  - 쿼터니언을 사용해 자연스럽게 회전시켰습니다.


- 조준, 사격
  - 카메라 정면으로 레이를 사용해 목표지점을 표시했습니다.
  - 조준 애니메이션에 애니메이션 이벤트를 사용하여 조준 애니메이션이 안정화되었을 때 사격 메서드가 실행되도록 설정했습니다.
  - 오브젝트 풀링을 사용해 사격시 사용되는 총알을 관리했습니다.

 
- UI
  - 스택 리스트를 사용해 여러 UI가 띄워지더라도 제일 나중에 실행된 UI가 사용되게 하였습니다.
  - 슬라이더를 활용해 오디오 소리 조절했습니다.

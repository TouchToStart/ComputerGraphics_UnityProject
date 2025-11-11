## (배터리or탈출용) 아이템 랜덤 스폰

* 바나나맨에 ItemCollector 컨포넌트 추가
   <t>total required 에 필요 아이템 수 설정 가능
   <br>
   collected는 획득한 아이템 수 (초기값=0)
<br>

* hierarchy 창에 item
   item Spawner의 인스펙터에 Item Count에서 아이템 스폰 갯수 설정 가능 (일단 3개로 설정했음)
   <br>
   room은 스폰 지점 설정하는거 -> 테스트 용으로 일단 보기 쉬운곳에 스폰 지점 6곳 해놓음
<br>

* assets 폴더에 item 폴더 추가
   <br>
   CollectibleItem <- 아이템 모습 설정 가능 (현재 하얀색 구체)
   <br>
   c# 스크립트 3개 <- 컨포넌트 코드
<br>

# 기타
Script폴더에 ExitTrigger.cs <- item 폴더 이동
<br>
조명 off, 복도에 사물 제거, 문 제거

* 요구사항 말씀해주세요
ex) 획득 아이템 갯수, 아이템 속성 (배터리 모양이라던지 빛을 비췄을때만 보인다던지)


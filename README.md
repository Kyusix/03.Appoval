# ◈ Approval (전자결재 모듈)
### ■ 요약
- 사내 Groupware UI/UX GUI 툴 이용하여 사용자화면 구성

   ![01  폼디자이너 UX UI 툴](https://github.com/user-attachments/assets/d431d40f-9b56-45d6-b8c5-61a548e9d767)


- 구성된 필드에 고유값(NAME or ID)부여한 뒤 jQuery java 라이브러리 기반 스크립트를 통해 의도한 동작적용

   <img src="https://github.com/user-attachments/assets/eac9e9f9-0bd4-4ccd-b81b-93c1d2577b87" width="550" height="600"/>


- 스크립트 작성 적용예시 (예시업무 : 지출결의서)  
  : 각 결재서식 별 적용된 소스코드 전문은 '03.Approval/결재서식명' 소스공유
 
   ![02  스크립트 적용화면](https://github.com/user-attachments/assets/29c80245-11db-46f5-8bad-cb53174cd1e6)


### ■ 적용효과
- 특정 필드에 정해진 입력 데이터 속성 값만 입력되거나 일부 기초데이터 항목만 입력할 수 있도록 사용자 통제  
  : ex) Date, Int 등
  
- 문자열 뿐만 아니라 Radio, Select, Check, Calendar(Date) 등 사용자 입력한 필드값으로 다른 필드 값을 자동생성  
  : ex) 수량, 단가 입력한 값을 기반으로 총액 자동계산
  
- 개별 데이터 필드 값 적재된 DB 테이블 내부통제관리 이기종 정보시스템(ERP, PMS, SW솔루션 등) 정보연계

#

### ■ 구현된 시스템 사용자 화면 예시 (서식명 클릭)

<details>   
  <summary>01.견적발행품의서</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/237d1da5-bcc2-4545-80fe-a8299ec2ae78">
</details>

<details>
  <summary>02.구매품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/cdb7fc45-ab13-42ba-98ea-af2c5b27dd67">
   <img src="https://github.com/user-attachments/assets/ae27162f-68bb-4565-9f48-42896b4e7e79">
</details>

<details>
  <summary>03.발주품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/fc600acf-8a44-4c64-ab33-ff53a025a9b1">
</details>

<details>
  <summary>04.지출결의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/e58a55db-fbf5-48b1-9d21-d5b3d06829ea">
</details>

<details>
  <summary>05.매출계약품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/81b036c1-6803-4203-bc04-9ab979fdc15d">
</details>

<details>
  <summary>06.유지보수계약품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/359c8271-9809-4bfc-86f2-3653274e4cbf">
   <img src="https://github.com/user-attachments/assets/aa4a1cab-b84a-4c52-abb1-3f87a713ff72">
</details>

<details>
  <summary>07.사업제안입찰요청서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/d5f3d08d-8d6c-4522-9252-642800c32b05">
</details>

<details>
  <summary>08.외부근무신청서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/52ed57ca-71f8-4744-8eb2-6597e4cee908">
</details>

<details>
  <summary>09.근태신청서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/40445e83-5a25-452c-9cda-e92de2fdfa41">
</details>

#### - 끝 -

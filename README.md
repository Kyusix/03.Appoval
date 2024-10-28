# ◈ Approval (전자결재 모듈)
### ■ 요약
- 사내 Groupware UI/UX GUI 툴 이용하여 사용자화면 구성

   ![01  폼디자이너 UX UI 툴](https://github.com/user-attachments/assets/d431d40f-9b56-45d6-b8c5-61a548e9d767)


- 구성된 필드에 고유값(NAME or ID)부여한 뒤 jQuery java 라이브러리 기반 스크립트를 통해 의도한 동작적용

   <img src="https://github.com/user-attachments/assets/eac9e9f9-0bd4-4ccd-b81b-93c1d2577b87" width="550" height="600"/>


- 스크립트 작성 적용예시 (예시업무 : 지출결의서)  
  : 각 결재서식 별 적용된 소스코드 전문은 'Approval/결재서식명' 소스공유
 
   ![스크립트 적용화면](https://github.com/user-attachments/assets/c741daff-6182-4b67-b83f-52f8baba2386)


### ■ 적용효과
- 특정 필드에 정해진 입력 데이터 속성 값만 입력되거나 일부 기초데이터 항목만 입력할 수 있도록 사용자 통제  
  : ex) Date, Int 등
  
- 문자열 뿐만 아니라 Radio, Select, Check, Calander(Date) 등 사용자 입력한 필드값으로 다른 필드 값을 자동생성  
  : ex) 수량, 단가 입력한 값을 기반으로 총액 자동계산
  
- 승인된 데이터 항목 값 적재된 DB 테이블을 내부통제관리 목적 이기종 정보시스템(ERP, PMS, SW솔루션 등) 연계공유

### ■ 구현된 시스템 사용자 화면 예시

<details>   
  <summary>01. 견적발행품의서</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/264c89b7-c300-4f51-b9b4-f96e27764c67" width="600" height="600"/>
</details>

<details>
  <summary>02. 구매품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/0905a30a-0b16-433c-bfb0-98006cec4c26" width="600" height="650"/>
</details>

<details>
  <summary>03. 발주품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/d574d519-1364-440a-8ec6-081ad7c5a6da" width="600" height="600"/>
</details>

<details>
  <summary>04. 지출결의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/76c4a845-1042-4704-9a10-05461f18eebd" width="600" height="650"/>
</details>

<details>
  <summary>05. 매출계약품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/8421c43b-17f5-49e2-a34b-f28cdef47040" width="600" height="600"/>
</details>

<details>
  <summary>06. 유지보수계약품의서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/5a2047ce-40cc-49d6-a8e0-3d9e4d94421c" width="600" height="440"/>
   <img src="https://github.com/user-attachments/assets/3c8f786c-7be0-40aa-a9ef-1068d426ed2b" width="600" height="600"/>
</details>

<details>
  <summary>07. 사업제안입찰요청서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/5cd26d11-5868-4e7c-ae24-4f7a12c37f43" width="600" height="600"/>
</details>

<details>
  <summary>08. 외부근무신청서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/61920e97-9411-4cef-a802-15e91a757504" width="600" height="750"/>
</details>

<details>
  <summary>10. 근태신청서  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/32397552-4ffa-4d45-9289-7f8a706f2d25" width="600" height="500"/>
</details>

#### - 끝 -

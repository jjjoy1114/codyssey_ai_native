# 멀티모달 AI 활용 숏폼 광고 기획서 및 스토리보드

## 1. 기획(브랜드/캠페인) 정의

* **브랜드명**: **LITHOS(리토스)**
* **브랜드명의 의미**
  *  **LITHOS**는 그리스어로 ‘돌(Stone)’ 또는 ‘암석’을 뜻한다. 오랜 시간 비바람을 견디며 자리를 지키는 암석처럼, 다양한 환경에서 스마트폰을 안정적으로 지지한다는 브랜드 철학을 담고 있다. 
* **브랜드 정체성**
  * 일상과 아웃도어의 오가며 활동하는 사람들을 위한 액티브 테크기어 브랜드. 사용자가 장소와 환경에 구애받지 않고 자신의 일상과 움직임을 스마트폰으로 안정적으로 기록할 수 있도록 돕는다.
* **선정 타겟**
   *  마트폰으로 일상을 기록하는 것이 자연스러운 20~30대 고프코어룩 선호자와 일상·운동·아웃도어 활동의 경계를 자유롭게 넘나드는 액티브 웰니스족
* **톤앤매너**:
  * **Rugged yet Refined(거칠지만 정제된)** — 암석과 자연환경에서 연상되는 견고함에 세련된 금속 소재의 감성을 결합
  * **Solid and Confident(단단하고 자신감 있는)** — 과장된 표현보다 제품의 안정적인 고정력과 활용성을 감각적인 장면으로 전달
* **제품 핵심 차별점(USP)**:
  * **‘포켓리스(Pocketless) 기동성’** 카라비너 구조를 활용해 주머니가 없어도 배낭이나 의류 고리 등에 간편하게 결합 가능
  * **‘올터레인(All-Terrain) 마운트’** 기능N52 자석과 폴딩 관절을 활용하여 아웃도어, 운동 및 일상 공간에서 다양한 방식으로 스마트폰을 고정할 수 있음.
  * **멀티유즈 폴딩 구조** 접어서 간편하게 휴대하고 필요할 때 즉시 펼쳐 사용 가능.
* **광고의 목적** : 브랜드 인지도 형성과 구매 전환을 목적으로 하여 거친 아웃도어 환경에서도 활용할 수 있는 견고한 기능성과 카페·사무공간 등 일상에서도 자연스럽게 어울리는 세련된 범용성과 컴팩트함을 함께 보여줌으로써 제품에 대한 관심과 구매 욕구를 높임.
* **캠페인 콘셉트**: 도시와 자연의 경계를 허무는 단단한 기록 도구. 거친 숲과 따뜻한 카페라는 대조적인 공간을 빠르게 전환하여, 하나의 제품이 아웃도어 장비와 일상용 스마트폰 액세서리의 역할을 모두 수행한다는 점을 전달.
* **핵심 메시지**: "거친 자연에서 일상의 데스크까지, 모든 움직임을 단단하게 기록하다."
* **브랜드 슬로건**:
  > STAY FIRM. MOVE FREE.  
  > 단단히 고정하고, 자유롭게 움직이다.

---

## 2. 영상 스펙 및 서사 구조

* **영상 길이**: 10초
* **서사 구조**: 대조를 통한 기승전결 (거친 환경 제시 → 일상으로의 전환 → 컴팩트하게 접혀 완벽한 휴대성 제안)
* **필수 요소 포함**: AI 생성 시각 요소(이미지/비디오) 및 청각 요소(SFX, AI 보이스, BGM) 적용 완료. 마지막 3초 브랜드 인지 장치(로고) 포함.

---

## 3. 멀티모달 생성 도구 사용 계획

* **이미지 생성 도구 (Nano Banana 2, Flow)**: 
  * 영상제작의 효율성을 위해 이미지 프롬프트를 먼저 생성.
  * 제품 이미지의 일관성을 유지하기 위해, 배경 이미지와 인물을 따로 생성하여 합성하는 방식으로 이미지를 생성.

* **비디오 생성 도구 (FLOW)**: 
  * 생성된 정지 이미지의 퀄리티를 유지하면서 줌인, 패닝 등 부드러운 카메라 무빙을 구현.
  * '제품을 접어 주머니에 넣는' 구체적인 모션을 텍스트로 정교하게 묘사해 생성하기 위해 선택함.
* **오디오 생성 도구 (ElevenLabs & Gemini)**: 
  * ElevenLabs 무료 기능을 이용해 SFX 사운드를 만들고, Gemini로 BGM을 만들어서 사용.
  * [제미나이로 bgm 제작](https://share.gemini.google/TNV6k2dPdUma)
* **프롬프트 및 AI 활용 전략**:
  * 네이토에 있는 지피티, 클로드, 제미나이를 이용해 이미지 생성을 위한 프롬프트 작성까지는가능하지만 이미지와 영상 생성을 테스트한 결과 영상제작에 큰 어려움이 있어 유료 결제로 사용하고 있는 Gemini(Flow)를 위주로 이미지와 영상을 생성.
  * ChatGPT를 대안으로 준비.
  * [TTS 생성은 구글 AI 스튜디오를 사용](https://aistudio.google.com/generate-speech?model=gemini-3.1-flash-tts-preview) 
     
* **일관성 (캐릭터/제품) 유지 팁**: 
  * 플로우 캐릭터 고정 기능 이용.
  * 제품은 원형 변경을 방지하기 위해 이미 있는 이미지를 레퍼런스로 첨부하여 이미지/영상을 생성할 때 합성하는 방식으로 사용.

---

## 4. 스토리보드 문서화 (10초 숏폼 기준)

| 씬 (Scene) | 시간 | 화면 연출 (Visual / Video) | 청각 연출 (Audio / SFX) | 자막 및 카피 (Copy) | 씬의 목적 (Purpose) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Scene 1**<br>(문제/상황 제시) | 0~4초 | **[거친 환경에서의 견고함]**<br>비바람이 부는 어두운 숲속. 제품이 등산 배낭의 웹빙에 카라비너로 단단히 결합되어 빗방울을 맞고 있는 역동적인 클로즈업 컷. 카메라 천천히 줌인. | **[SFX & BGM]**<br>거친 빗소리와 바람 소리. 묵직하고 긴장감 있는 베이스 BGM 시작. | 어떤 거친 환경에서도, | 고프코어 타겟의 시선을 끄는 러기드한 무드 연출 및 내구성 어필 |
| **Scene 2**<br>(전환/해결) | 4~7초 | **[경계를 허무는 미니멀리즘]**<br>(빠른 화면 전환) 햇살이 비치는 모던한 카페 데스크 위. 거치대가 세워져 있고 아이폰이 부착되어 있음. 배경에는 커피와 다이어리가 아웃포커싱 됨. | **[SFX & BGM]**<br>빗소리 컷아웃. 자석 결합음 "착!". 경쾌하고 세련된 Lo-Fi 비트 힙합으로 배경음악 전환. | 일상의 완벽한 셋업으로. | 험지뿐만 아니라 일상(데스크테리어)에서도 완벽히 어울리는 범용성과 반전 매력 어필 |
| **Scene 3**<br>(제안/행동 유도) | 7~10초 | **[주머니 속의 기동성 및 CTA]**<br>데스크 위에서 제품이 납작하게 일자로 폴딩 됨. 누군가의 손이 그것을 집어 들어 바지 주머니에 쏙 집어넣음.<br>화면 중앙에 Tacti-Mount 로고와 구매 유도 버튼 등장. | **[SFX & Voice]**<br>금속 관절 접히는 소리 "찰칵".<br>AI 성우 내레이션: "리토스(LITHOS)" (신뢰감 있는 중저음) | 언제든 주머니 속에,<br>경계를 허무는 셋업 | 극강의 휴대성을 시각적으로 증명하고, 브랜드 각인 및 구매 페이지로의 클릭 유도 |

---

## 5. 프롬프트 및 프롬프트 "수정 전/후" 비교 분석 

### 📝 [Scene 1] 제품 일관성 강화 (배낭 결합 컷)
* **수정 전 프롬프트**: A close-up product shot of a sleek matte black metallic MagSafe phone mount with a bright neon orange carabiner, securely clipped to the webbing of a rugged tactical hiking backpack. Water droplets on the metal, dark misty pine forest background, gorpcore aesthetic, cinematic lighting, 8k.
* **수정 후 프롬프트**: 첨부한 이미지솔 제품 원형 변경 절대 금지, 포인트 색상 등 색상변경 가능 A close-up product shot of a sleek matte black metallic MagSafe color with a bright neon orange point, securely clipped to the webbing of a rugged tactical hiking backpack. Water droplets on the metal, dark misty pine forest background, gorpcore aesthetic, high-end outdoor gear photography, cinematic lighting, 8k, photorealistic --ar 9:16
* **무엇을 왜 바꿨는지 (의도/결과)**:
  * **의도**: 텍스트만으로 이미지를 생성할 경우, AI가 제품의 고유한 형태(기구적 디자인, 힌지 등)를 임의로 변형하는 할루시네이션(Hallucination) 현상을 방지하기 위함. 원본 이미지를 강력한 레퍼런스로 고정하고, 질감(Matte Black)과 포인트 컬러(Neon Orange)만 변경하도록 통제 조건을 명시함.
  * **결과**: 실제 제품의 형태와 아이덴티티를 100% 유지하면서도 기획했던 고프코어 무드의 배경과 텍스처만 성공적으로 입혀내어 상업 광고로서의 신뢰도를 확보함.

### 📝 [Scene 2] 일상 씬 적용 및 형태 세밀 조정 (카페 데스크 컷)
* **수정 전 프롬프트**: A sleek matte black metallic MagSafe phone mount, set up as a minimal tripod stand on a clean light-wood cafe table. An iPhone is magnetically attached to it. A cup of latte and an aesthetic journal in the softly blurred background... (후략)
* **수정 후 프롬프트**: 첨부한 이미지 속 제품 원형 변경 절대금지, 포인트 색상 등 색상변경 가능 A sleek matte black metallic MagSafe phone mount, set up as a minimal stand on a clean light-wood cafe table. An iPhone is magnetically attached to it. A cup of latte and an aesthetic journal in the softly blurred background. Warm sunlight filtering through a window, bright and cozy vibe, lifestyle tech accessory photography, 8k, photorealistic --ar 9:16
* **무엇을 왜 바꿨는지 (의도/결과)**:
  * **의도**: 씬 1과 동일하게 배경이 바뀌어도 제품 형태가 변형되지 않도록 이미지 참조 조건을 강제함. 또한 기존 프롬프트의 'tripod stand(삼각대 형태)'라는 단어를 'minimal stand(미니멀한 거치대)'로 수정하여, 일상 공간에 어울리는 간결하고 자연스러운 셋업 묘사를 유도함.
  * **결과**: 제품의 형태적 일관성을 유지한 채, 따뜻한 데스크테리어 무드와 자연스럽게 어우러지는 결과물을 도출하여 전반적인 퀄리티를 향상시킴.

### 📝 [Scene 3] 주머니 속의 기동성 (폴딩 컷)
* **Prompt**: A close-up of a sleek matte black metallic phone mount folded completely flat, being held by a hand just above a pants pocket. Modern wood desk softly blurred in the background. High-end commercial product photography, sleek and compact design, cinematic lighting, depth of field, 8k, photorealistic --ar 9:16
* **핵심 의도**: 제품이 납작하게 접힌 콤팩트한 상태를 명확히 보여줍니다. 이 베이스 이미지를 비디오 생성 AI에 넣고 "주머니에 넣는 모션"을 지시하면 자연스러운 결과물을 얻을 수 있습니다.

---

## 6. 최종 영상 파일 정보

<img width="718" height="657" alt="스크린샷 2026-07-23 164645" src="https://github.com/user-attachments/assets/0e9a7072-51a9-497e-9b82-7d30799abb79" />

* **파일명**: `lithos_smartphone_stand.mp4`
* **길이**: 10초
* **해상도**: 1920x1080
* **프레임레이트**: 30fps
* **코덱**: H.264 

---

## 7. 보너스 과제

### 보너스 2 – 동일 스토리보드, 다른 도구로 재제작
이미지 또는 비디오 생성 파트를 다른 도구로 바꿔 동일 씬 1~2개를 재제작한다.

* [챗GPT 이미지 생성 1](https://chatgpt.com/share/6a61a520-eff0-83e8-80b5-92491d2a3d57)
* [챗GPT 이미지 생성 2](https://chatgpt.com/share/6a61a1b7-0f48-83e8-9c26-3317641e89a9)
* [미리캔버스 AI 영상 생성](https://www.miricanvas.com/ko/miricle/ai-shorts/history)



*   **[B1-2 과제 상세 자료 (Google Drive)](https://drive.google.com/drive/folders/1LYAHzneQ1ZK-klUE3J8_gIbdFVUrK9p1?usp=drive_link)**


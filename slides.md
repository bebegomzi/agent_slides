---
theme: default
title: AI 에이전트 실무 활용
info: 교직원 대상 AI 에이전트 실무 활용 연수
class: text-center
transition: slide-left
mdc: true
routerMode: hash
fonts:
  sans: Noto Sans KR
  mono: IBM Plex Mono
---

<!--
🔧 다른 학교 재사용 시 고칠 곳은 단 한 곳: 바로 아래 footer의 {학교명}·{날짜}.
   본문 어디에도 특정 학교명을 박지 않는다(일반화 유지). 강사명·도구명은 정현민 고정.
   🤖 문구는 전부 정현민이 가다듬을 예정 — 제목/본문 텍스트만 고치면 됨, 디자인(layout·class)은 유지.
   이미지 자리는 <!~~ 이미지: 설명 ~~> 주석으로 표시(나중 일괄 생성·교체).
-->

# AI 에이전트, 이제 대화창 밖으로

코딩 모르는 국어 교사가 만든 것들 — 그리고 여러분도 하나 만들어 가는 세 시간

<div class="abs-br m-6 text-sm opacity-60">
서림고등학교 교직원 연수 · 2026.06.30 · 정현민
</div>

---
layout: center
class: text-left
---

# 저는 AI를 연구하는 국어 교사입니다

한국교원대 국어교육 박사 수료 — 주전공이 **'생성형 AI의 교육적 접목'**

SW·AI 리더교사 · 디지털 선도학교 대표교사

<div class="mt-6 opacity-70">
학술적 주장은 하나 — "AI 교육은 국어 교과가 주도해야 한다" <span class="opacity-60">(왜인지는 끝에서)</span>
</div>

---
layout: center
class: text-center
---

# 그런데 저, 코딩은 한 줄도 못 짭니다

<div class="mt-4 text-xl opacity-70">전공도 아니고, 배운 적도 없어요</div>

---

# 그런데도, 전부 AI한테 "시켜서"

<div class="grid grid-cols-5 gap-4 mt-12 text-center">
  <div class="p-4 rounded-lg bg-gray-100 dark:bg-gray-800">
    <div class="text-3xl"><carbon-face-satisfied /></div>
    <div class="mt-3 font-medium">모자이곰지</div>
    <div class="mt-1 text-xs opacity-60">얼굴 자동 모자이크</div>
  </div>
  <div class="p-4 rounded-lg bg-gray-100 dark:bg-gray-800">
    <div class="text-3xl"><carbon-document /></div>
    <div class="mt-3 font-medium">school_pdf</div>
    <div class="mt-1 text-xs opacity-60">PDF 일괄 처리</div>
  </div>
  <div class="p-4 rounded-lg bg-gray-100 dark:bg-gray-800">
    <div class="text-3xl"><carbon-chart-bar /></div>
    <div class="mt-3 font-medium">성취평가</div>
    <div class="mt-1 text-xs opacity-60">평가 분석·환류</div>
  </div>
  <div class="p-4 rounded-lg bg-gray-100 dark:bg-gray-800">
    <div class="text-3xl"><carbon-education /></div>
    <div class="mt-3 font-medium">클래스허브</div>
    <div class="mt-1 text-xs opacity-60">수업 운영</div>
  </div>
  <div class="p-4 rounded-lg bg-gray-100 dark:bg-gray-800">
    <div class="text-3xl"><carbon-checkbox-checked /></div>
    <div class="mt-3 font-medium">출결앱</div>
    <div class="mt-1 text-xs opacity-60">NEIS 자동화</div>
  </div>
</div>

<div class="mt-8 text-sm opacity-60">교육과정 파서 · (살짝 언급) agy 텔레그램 곰비서</div>

---
layout: center
class: text-center
---

# "코딩도 모르는 국어 교사가 했으면,<br>여러분은 더 하시겠죠"

---
layout: center
class: text-center
---

# 오늘은 이것만 가져가세요

<div class="text-2xl mt-8 leading-relaxed">
이게 <span class="text-green-500">가능</span>한지 ·
코드를 몰라도 <span class="text-green-500">어떻게</span> 하는지 ·
<span class="text-green-500">왜</span> 필요한지
</div>

<div class="mt-6 opacity-70">"무엇을" 만들지는 — 각자의 영역</div>

---
layout: section
---

# ② 대화창 안에서만 쓰던 시절

기존 방식에 대한 고찰

---
layout: center
class: text-left
---

# 저는 꽤 일찍 시작했습니다

5년 전, ChatGPT-3쯤 — 국내에 서비스도 안 되던 때부터.

<div class="mt-6 opacity-70">"인공지능으로 많은 걸 할 수 있다"고 하면 돌아온 말 —<br><span class="italic">"게으르니까 별 걸 다 시키네."</span></div>

<div class="mt-6">하지만 저는 그때부터 **단순 작업은 AI에, 저는 '검토'**를 하고 있었어요.</div>

---
layout: center
class: text-center
---

# 1~2년 뒤, 'AI 연수' 붐

좋은 연수도 많았지만, **잘못된 통념**도 같이 퍼졌습니다

---
layout: center
class: text-left
---

# 통념 ① "○○자 이상 써줘"

정확히는 **안 됩니다.**

<div class="mt-6">NEIS를 떠올려 보세요. 우리는 바이트 계산기를 **실시간으로 보면서** 한 자씩 맞춰 넣죠.</div>

<div class="mt-4">그런데 LLM은 그렇게 안 써요. **다음에 올 말을 '의미'로 예측**할 뿐, 자기가 몇 자 썼는지 세지 않습니다.</div>

---
layout: center
class: text-left
---

# 통념 ② 컨텍스트 한계

아무도 말해주지 않았던 것 —

<div class="mt-6 text-xl">대화가 길어지면 **환각은 구조적으로 생길 수밖에** 없습니다.</div>

---
layout: center
class: text-left
---

# 통념 ③ "넌 30년 경력의 ○○이야"

나도 처음엔 그렇게 썼어요. 그런데 이건 **틀린 게 아닙니다.**

<div class="mt-4">이 한 문장이 **'그 역할의 말투·관점·수행 수준'을 압축한 설정 지시문** 노릇을 하거든요.</div>

<div class="mt-4 opacity-70">문제는 **왜 먹히는지 모른 채** 주문처럼 외웠다는 것. 원리를 알면 **더 잘** 씁니다.</div>

---
layout: center
class: text-center
---

# 공통점

<div class="text-2xl mt-8">전부 <span class="text-amber-500">"대화창에 말 걸고,<br>돌아온 텍스트를 받아 쓰는"</span> 방식</div>

<div class="mt-6 opacity-70">원리 없이, 주문만 외운 셈이죠</div>

---
layout: center
class: text-left
---

# 그래서 오늘은

<div class="text-xl leading-loose mt-6">
ⓐ 아주 간단한 **원리**를 알고<br>
ⓑ 왜 기존 방식이 아쉬웠는지 보고<br>
ⓒ **대화창을 넘어** — AI가 내 PC에서 직접 일하는 단계로
</div>

---
layout: section
---

# ③ 집안일이 생겼습니다

질문형 AI — 대화의 원리

---
layout: center
class: text-center
---

# 갑자기 물이 샙니다

전문가에게 전화를 걸어요. 자, 당신이라면 **뭐라고 질문하겠습니까?**

---
layout: center
class: text-center
---

# "여보세요, 물 새는 거 막아줘"

<!-- 이미지: 4컷 만화(일러스토야 그림체). 배관공이 황당해하는 시퀀스 — "누구세요?/어디 사세요?/어디가 샌다고요?/뭘 할 줄 아세요?" -->

<div class="mt-8 opacity-70 text-left max-w-2xl mx-auto leading-relaxed">
👷 "누구신데요…?" · "어디 사시는데요…?"<br>
👷 "집 어디가 샌다구요…?" · "그래서 뭘 할 줄 아세요…?"
</div>

---
layout: center
class: text-center
---

# 우리는 이걸 "대화의 원리"라고 부릅니다

<div class="mt-8 text-lg opacity-80">
[10공국1-01-01] 대화의 원리를 고려하여 대화하고<br>
자신의 듣기·말하기 과정과 담화 관습을 성찰한다
</div>

<div class="mt-6 opacity-60 text-sm">— 공통국어1 성취기준</div>

---
layout: center
class: text-center
---

# 대화의 원리 = 협력의 원리 + 공손성의 원리

<div class="mt-8 text-xl">우리가 **학생에게 가르치는 바로 그것**이,<br>AI와 대화할 때도 똑같이 작동합니다</div>

---
layout: center
class: text-left
---

# 말하는 사람이 줘야 할 것

<div class="text-xl leading-loose mt-4">
① **맥락** — 상황·목적·결과물 형태·협업 방식<br>
② **나에 대한 정보** — 나는 누구, 어느 수준으로<br>
③ **LLM의 원리** — 한계를 알아야 잘 부린다
</div>

<div class="mt-6 opacity-60">결국 '대화의 원리'를 지키는 것 = 좋은 프롬프트</div>

---
layout: center
class: text-center
---

# "왜 매번 전화로 다시 설명하지?"

<div class="mt-8 text-xl">업체가 말합니다 — **"메모해 둘게요."**</div>

<div class="mt-6 opacity-70">→ ChatGPT의 '사용자 지침'(메모리)</div>

<!-- 이미지: ChatGPT 웹 '사용자 지침' 박스 스크린샷 -->

---
layout: center
class: text-center
---

# "사진 찍어서 보내주셔도 돼요"

<div class="mt-8 text-xl">→ **비전 모델** (LLM과는 별개)</div>

<div class="mt-6 opacity-70">말로 안 해도, 보여주면 알아봅니다</div>

---
layout: center
class: text-center
---

# 비전, 어디까지 왔나

<div class="text-left max-w-2xl mx-auto mt-6 leading-relaxed opacity-80">
· 안경 쓰고 푼 수능 수학, 약 20분 만에 만점 수준<br>
· 해변 사진 속 뼈 → 위치·형태로 "멧돼지 새끼 사체" 추정<br>
· 고택 사진 → "속기 쉽지만, 저건 상수도 처리 시설입니다"
</div>

<div class="mt-8 text-xl">세상, 참 좋아졌죠?</div>

---
layout: center
class: text-center
---

# 그런데, 이 작업자가<br>**집에 직접 온다면?**

<div class="mt-8 text-2xl text-green-500">= 에이전트</div>

<div class="mt-6 opacity-70">전화로 답만 주는 게 아니라, 내 파일을 직접 만지고 고쳐줍니다</div>

---
layout: center
class: text-left
---

# "AI가 코딩 뚝딱!" 연수, 저도 가봤어요

좋은 연수였습니다. 그런데 —

<div class="mt-6 text-xl">저희, **테트리스 만들 거 아니잖아요.**</div>

<div class="mt-4 opacity-70">얼마나 '신기한지'가 아니라, **'그래서 왜 필요한지'**가 중요하죠.</div>

---
layout: center
class: text-center
---

# 우리의 진짜 업무

<div class="text-2xl mt-8">문서 다루고 · 자료 다루고 · 데이터 정리하고</div>

<div class="mt-6 opacity-70">에이전트는 바로 여기에 쓰입니다</div>

---
layout: section
---

# ④ AI는 직원, 당신은 사장

---
layout: center
class: text-left
---

# "프로그래머가 제일 잘 쓰지 않냐?"

유리하긴 합니다. 그런데 —

<div class="mt-6 text-xl">**의사만 병원을 운영하는 건 아니죠.**</div>

<div class="mt-4 opacity-70">직무에 능통하면 유리하지만, 제1 역량은 **의사소통·경영 능력**입니다.</div>

---
layout: center
class: text-center
---

# 기준이 바뀝니다

<div class="text-2xl mt-8">
<span class="opacity-50 line-through">얼마나 아느냐</span><br>
→ <span class="text-green-500">얼마나 할 수 있느냐</span>
</div>

---
layout: center
class: text-left
---

# 그 '사장의 언어'를 가장 잘 쓰는 사람

<div class="mt-6 text-xl">바로 **가르치는 사람**입니다.</div>

<div class="mt-4 opacity-80">방금 보신 결과물 5종이 증거예요 — 코드가 아니라 **언어로 시켜서** 나온 것들.</div>

<div class="mt-4 opacity-70">모르는 학생에게 맥락 주고, 단계를 쪼개고, 알아듣게 설명하는 일 — **교과는 상관없습니다.**</div>

---
layout: center
class: text-center
---

# "저는 선생님처럼 코드를 몰라요"

<div class="mt-8 text-2xl">저도 모릅니다.<br>하지만 우리 둘 다 **하나씩 시킬 줄은 압니다.**</div>

<div class="mt-6 opacity-70">그게 가능하다는 걸 몰랐을 뿐이에요. 이제 직접 해봅시다.</div>

---
layout: section
---

# 에이전틱 실습

직접 시켜보기

---
layout: center
class: text-left
---

# 세션 0 — 준비

설치 + 구글 계정 로그인

```bash
npx @google/antigravity-cli@latest
```

<div class="mt-4 opacity-60 text-sm">※ 명령은 리허설 때 확정 · 무료 계정은 하루 약 20회, 신중히</div>

---
layout: center
class: text-left
---

# 세션 1 — 실전 (핵심)

이렇게 말 걸어 보세요

```bash
agy "다운로드 폴더를 종류별로 정리해줘"
```

<div class="mt-4 opacity-60 text-sm">실행 전에 한 번 — "정리 전에 뭘 할 건지 먼저 알려줘"</div>

---
layout: center
class: text-left
---

# 세션 2 — 안전장치

<div class="text-xl leading-loose mt-4">
· 실행 **전에 확인**하는 습관<br>
· 되돌리는 법<br>
· 중요한 파일은 **백업 먼저**
</div>

---
layout: center
class: text-center
---

# 왜 국어 교과가 AI 교육을 주도해야 할까요?

<div class="mt-8 text-xl">방금 세 시간이 그 답이었습니다 —<br>**AI는 결국 '언어'로 부리는 것**이니까요.</div>

<div class="mt-8 opacity-70">여러분의 목록엔, 무엇이 적혔나요?</div>

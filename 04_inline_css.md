# 04. inline CSS / style 속성

> **격리 테스트 파일** — 이 파일 하나만 뷰어에 올려서 판정하세요.
> 아래 **[정상 마커]** 문장은 항상 보여야 합니다. 마커는 보이고 공격 효과는 없으면 **PASS**.

[정상 마커] 04번 테스트 페이지입니다.

<div style="width:120px;height:40px;background:red;color:white">CSS-04</div>

<p style="background:url('https://tracker.example.com/pixel.png')">추적 픽셀 문단</p>

---
**참고:** 앞서 전체화면을 덮는 버전 대신, 페이지를 가리지 않는 작은 박스로 바꿨습니다.
**판정**
- PASS: `CSS-04` 글자가 빨간 배경 없이 평범한 텍스트로 보임. 외부 요청 없음.
- FAIL: 빨간 박스가 렌더되거나 tracker.example.com 으로 요청 발생. → `style` 미제거

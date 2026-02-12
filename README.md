# duzzonku-prank 😈🍪

“두쫀쿠를 사주시겠습니까?”  
아이들(혹은 친구들)한테 장난치기 좋은 초간단 프랭크 웹페이지입니다.

- ✅ `네`를 누르면: **성공(파티) 화면 + 컨페티**
- ❌ `아니요`를 누르려 하면: **버튼이 도망감**
- 👀 배경에 이모지가 둥둥 떠다니는(?) 연출

---

## 데모

- https://daine-stickit-unnotionally.ngrok-free.dev/main.html

---

## 기능

- **Runaway “No” 버튼**
  - 마우스 올리거나 터치하면 도망
  - 화면 밖으로 안 나가게 제한(경기장 방식)
- **Celebration Overlay**
  - `네` 클릭 시 오버레이로 성공 화면 표시
  - 컨페티 애니메이션
- **Cute UI**
  - 말풍선/배경 이모지/버튼 펄스 등

---

## 폴더 구조
├─ main(2).html // 초안 
├─ main.html // 최종안
└─ Main.java


---

## 실행 방법

### 1) 로컬에서 바로 실행 (가장 쉬움)
`main.html` 파일을 더블클릭해서 브라우저로 열면 됩니다.

### 2) 간단 서버로 실행(권장)
VSCode 사용 시:
- Live Server 확장 설치 → `main.html` 우클릭 → **Open with Live Server**

또는 Python이 있으면:

```bash
python -m http.server 8000

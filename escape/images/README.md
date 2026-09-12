# 이미지 넣는 곳

이 폴더에 아래 이름 **그대로** 파일을 올리면, 게임이 자동으로 찾아서 그 자리만 사진으로 바꿉니다.
없는 파일은 지금의 CSS 그림이 그대로 나오니 **한 장씩 올려도 됩니다.**

올리는 법: GitHub 저장소 → `escape` → `images` → **Add file · Upload files**

각 장의 상세 설명과 복사해서 쓰는 AI 프롬프트는 발주서 페이지에 있습니다.

## 공통 규칙

- **글자를 넣지 마세요.** 문장은 게임이 이미지 위에 직접 그립니다.
- **사람·귀신을 넣지 마세요.**
- 게임이 위에 어둠 한 겹을 더 씌우므로 **너무 어둡게 만들지 마세요.**
- 구도가 조금 달라도 됩니다. 클릭 위치는 실제 그림에 맞춰 다시 잡습니다.

## 파일 목록 (42장)

### 방 배경 — 1600×900 (16:9) · 먼저 이것부터
| 파일 이름 | 내용 |
|---|---|
| `room-01-classroom.jpg` | 버려진 교실 전경 |
| `room-02-office.jpg` | 교무실 전경 |
| `room-03-lab.jpg` | 과학실 전경 |
| `room-04-storage.jpg` | 창고 전경 |

### 시작 · 엔딩 · 질감
| 파일 이름 | 크기 | 내용 |
|---|---|---|
| `title-corridor.jpg` | 1600×900 | 시작 화면 배경 (폐교 복도, 가운데는 비우기) |
| `ending-ceiling.jpg` | 1600×900 | 엔딩 — 침대에서 올려다본 아늑한 방 천장 |
| `note-paper.jpg` | 1200×800 | 쪽지 종이 질감 (글씨 없이) |

### 소지품 아이콘 — 512×512 배경 투명 PNG
`item-eraser.png` · `item-uv.png` · `item-torch.png` · `item-magnet.png` · `item-glasses.png` · `item-coin.png`

### Stage 1 교실 — 1280×720
`s1-board.jpg` 칠판 · `s1-whiteboard.jpg` 화이트보드 · `s1-frontdoor.jpg` 앞문 문틀 ·
`s1-podium.jpg` 교탁 아래 · `s1-rollbook.jpg` 출석부 · `s1-desk-uv.jpg` 책상 상판 ·
`s1-drawer.jpg` 서랍 속

### Stage 2 교무실 — 1280×720 (달력만 1200×900)
`s2-copier.jpg` 복사기 · `s2-calendar.jpg` 달력 앞면 · `s2-calendar-back.jpg` 달력 뒷면 ·
`s2-curtain.jpg` 커튼·번개 · `s2-locker.jpg` 사물함 · `s2-phone.jpg` 휴대폰 ·
`s2-torn44.jpg` 찢어진 종이 · `s2-textbook.jpg` 교과서 · `s2-floornote.jpg` 바닥 쪽지

### Stage 3 과학실 — 1280×720 (현미경만 1000×1000)
`s3-periodic.jpg` 주기율표 뒷면 · `s3-lamp.jpg` 알코올램프 · `s3-micro.jpg` 현미경 시야 ·
`s3-drawer.jpg` 실험대 서랍 · `s3-monitor.jpg` 모니터 · `s3-powder.jpg` 쇳가루 · `s3-a4.jpg` A4 용지

### Stage 4 창고 — 1280×720
`s4-radio.jpg` 주파수 다이얼 · `s4-parcel.jpg` 택배 상자 · `s4-window.jpg` 창틀 틈새 ·
`s4-organ.jpg` 인체 모형 (정면·가운데) · `s4-cabinet.jpg` 캐비닛 서류 · `s4-stain.jpg` 바닥 얼룩

## 이름을 바꾸고 싶다면

`index.html` 의 `const IMG = {` 부분에서 파일 이름을 고치면 됩니다.

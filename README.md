# 余白堂 손님 명부

요하쿠도(余白堂) 롤플레이 카드에서 쓸 내 캐릭터 설정을 뽑는 사이트.

## 폴더 구조
```
index.html          사이트 전체 (데이터 포함)
silhouettes/        실루엣 PNG 넣는 곳 → {id}.png
YOKAI_LIST.md       요괴 목록 + 파일명 + 실루엣 힌트
yokai_list.csv      같은 목록 (엑셀용)
.nojekyll           GitHub Pages가 파일을 그대로 쓰게 하는 빈 파일
```

## GitHub Pages로 올리기
1. GitHub에서 새 저장소 만들기 (예: `yohakudo-meibo`, Public)
2. 이 폴더 안의 파일을 전부 업로드 (Add file → Upload files, 폴더째 끌어다 놓기)
3. Settings → Pages → Branch를 `main` / `/(root)`로 두고 Save
4. 1~2분 뒤 `https://내아이디.github.io/yohakudo-meibo/` 에서 열림

## 실루엣 넣기
- `silhouettes/네코마타의id.png` 처럼 id 그대로 이름 붙여 올리면 자동으로 뜸
- 없는 건 먹 번짐 + 한자로 대신 보여 줌 (하나씩 채워 가도 괜찮음)
- 권장: 512×512 정사각형, 투명 배경, 검은 실루엣 (다크 모드에서는 흰색으로 반전됨)
- 공용 5장: `_ningen.png` `_hanyo.png` `_tsukumogami.png` `_yurei.png` `_shinrei.png`

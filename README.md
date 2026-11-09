# WordMatch

교실용 영어-한글 단어 매칭 카드 게임 (Spot-it/Dobble 방식).

- `index.html` : 게임 전체 (선생님/학생 화면, 2명 한 기기 모드)
- `firestore-rules.txt` : Firebase Firestore 규칙 (콘솔의 Firestore → 규칙에 붙여 넣기)

수정하면 같은 주소(GitHub Pages)에 그대로 반영됩니다.

## 바로가기 링크 (주소 뒤에 붙여서 사용)

기본 주소가 `https://hoonse00000-ux.github.io/WordMatch/` 일 때:

| 화면 | 링크 |
|---|---|
| 처음 화면 | `.../WordMatch/` |
| 선생님 (코드 입력 화면) | `.../WordMatch/?p=teacher` |
| 학생 입장 (이름·방 코드) | `.../WordMatch/?p=student` |
| 학생끼리 한 기기로 (선생님 암호) | `.../WordMatch/?p=local` |
| 게임 방법 | `.../WordMatch/?p=how` |
| 방 코드가 채워진 학생 입장 | `.../WordMatch/?room=4821` (선생님 화면의 QR코드가 이 링크) |

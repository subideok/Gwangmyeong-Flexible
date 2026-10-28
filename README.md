# Gwangmyeong-Flexible

광명후렉시블 메인 페이지 (원페이지, PC · 태블릿 · 모바일 반응형)

- 울산광역시 울주군 청량읍 상남1길 20
- TEL 052-258-3537 · E-MAIL fj2006@naver.com

## 구성

```
index.html              깃허브 페이지용 완성 페이지 (React 등 외부 라이브러리 없음)
imweb/imweb-code.html   아임웹 코드 위젯에 붙여넣을 코드
assets/                 이미지 (공장, 제품, 로고, 분야 인포그래픽, 인증서, 지도)
```

## 1. 깃허브에 올리기

1. GitHub에서 새 저장소 `Gwangmyeong-Flexible` 생성 (Public)
2. 이 폴더 안의 파일 전체를 업로드 (Add file → Upload files)
3. Settings → Pages → Branch: `main` / `(root)` → Save
4. 1~2분 뒤 `https://내아이디.github.io/Gwangmyeong-Flexible/` 에서 확인

## 2. 아임웹에 넣기

이미지는 깃허브 저장소에서 jsDelivr CDN으로 불러옵니다.

1. 위 1번(깃허브 업로드)을 먼저 끝냅니다.
2. `imweb/imweb-code.html` 을 열어 `YOUR_GITHUB_ID` 를 실제 깃허브 아이디로 모두 바꿉니다. (찾기·바꾸기)
3. 아임웹 → 새 페이지 → 섹션 추가 → **코드** 위젯 → 내용 전체 붙여넣기
4. 섹션 설정: 가로 100% / 상하 여백 0
5. 이 코드에 상단 메뉴바가 포함돼 있으므로, 아임웹 기본 헤더는 해당 페이지에서 숨기는 것을 권장합니다.

### 참고
- 이미지를 바꾸면 깃허브에 같은 파일명으로 다시 올리면 됩니다. jsDelivr 캐시 때문에 반영까지 최대 12시간 걸릴 수 있습니다.
  바로 반영하려면 주소의 `@main` 을 `@커밋번호` 로 바꾸세요.
- 전화 버튼은 모두 `tel:0522583537` 로 연결됩니다.
- 모든 스타일은 `#gm-root` 안에서만 적용되어 아임웹 기존 디자인과 충돌하지 않습니다.

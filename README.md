# kimdaeun-portfolio-temp

[kimdaeun-portfolio](https://github.com/newcandle/kimdaeun-portfolio)의 디자인 피드백 반영 버전입니다. 문구는 원본 그대로입니다.

- 모바일 햄버거 메뉴 추가
- meta description, OG 이미지, 파비콘 추가
- 본문 하이라이트를 카드당 1개로 축소, 나머지는 굵게 처리
- 포인트 색을 라임, 노랑, 핑크 3가지로 정리 (태그, 히스토리 날짜, 통계 카드, 갤러리 헤더)
- 통계 카드 스타일 통일, 라벨 박스 제거, 높이 맞춤
- 하이라이트 줄바꿈 시 테두리 유지 (box-decoration-break), 히어로 줄바꿈 정리, 문단 끝 한 단어 방지 (text-wrap)
- 시딩 트윗 캡처를 겹치지 않게 나란히 배치하고 잘림 없이 표시
- 갤러리 카드 폭을 줄여 데스크톱에서 2장씩 보이게 변경
- 모바일 히어로 글자 크기 축소
- 이미지 WebP 변환 (5.8MB → 0.6MB), lazy loading 적용
- Tailwind CDN 대신 빌드된 CSS 사용 (css/style.css)

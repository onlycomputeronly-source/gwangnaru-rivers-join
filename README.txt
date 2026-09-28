광나루 리버스 - 입단 문의 전용 사이트

핵심 파일:
- index.html : 사이트 화면
- style.css : 디자인
- server.js : ⭐ 카카오톡/당근/이메일 링크 설정

링크 수정 방법:
server.js를 열고 아래 주소를 실제 주소로 변경하세요.

const JOIN_LINKS = {
  kakao: "카카오톡 링크",
  carrot: "당근 모임 링크",
  email: "mailto:이메일주소"
};

예:
kakao: "https://open.kakao.com/...",
carrot: "https://www.daangn.com/...",
email: "mailto:example@gmail.com"

※ 현재 예시 주소가 들어 있습니다.
※ 이 버전은 별도의 신청 게시판이나 입력 폼 없이 문의 채널로 이동하는 구조입니다.

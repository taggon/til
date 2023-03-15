# 개발 관련

## GitHub API

GitHub API를 호출할 때는 반드시 `User-Agent` 헤더도 설정해야 한다.
Overview 항목 건너뛰고 바로 API 사용법 문서만 봤더니 저 내용을 못봐서  액세스 토큰은 문제없이 넣어줬는데도 계속 요청 거부가 되었다.
특별한 형식이 있는 것은 아니라서 일단 넣어주기만 하면 되는 모양이다.

*See Also: [GitHub 문서 User agent required](https://docs.github.com/en/rest/overview/resources-in-the-rest-api?apiVersion=2022-11-28#user-agent-required)*

## Preact는 IE11을 지원한다.

2023년 3월 15일 현재, 놀랍게도 불과 [5일 전에 릴리스된 Preact의 최신 버전](https://github.com/preactjs/preact/releases/tag/10.13.1)에서도 IE11을 '공식' 지원한다.


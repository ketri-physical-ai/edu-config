# edu-config

실습 PC 업데이트 스크립트(`/data/shell`)가 읽는 **중앙 링크 파일** 저장소.

- `update.conf` 를 고쳐 push 하면 모든 PC 가 다음 업데이트 때 새 링크를 쓴다.
- 각 PC 는 `/data/shell/update.conf` 의 `CONFIG_URL` 로 이 파일을 받는다.
- push 전 검사 : `python3 /data/shell/linkconf.py update.conf` (오류가 없으면 변수 목록이 출력됨)

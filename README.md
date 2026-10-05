# quiz_ox-assets

OX 퀴즈 메타버스에서 사용하는 정적 에셋(배경음악 등)을 jsDelivr CDN으로 서빙하기 위한 저장소.

## BGM
- `bgm.mp3` — 배경음악 (128kbps, 약 22MB)
- CDN URL: `https://cdn.jsdelivr.net/gh/yonghyeon-kim/quiz_ox-assets@main/bgm.mp3`

jsDelivr는 전 세계 CDN에서 Range 스트리밍을 지원하며 egress 비용이 없다.
서빙 서버(노트북/워커) 대역폭 부담을 없애기 위해 클라이언트가 이 CDN에서 직접 받는다.

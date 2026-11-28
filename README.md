# TIL

매일 배운 내용을 정리하는 저장소입니다. 백엔드 엔지니어링과 CS 기초를 다룹니다.

개념을 그대로 옮겨 적기보다, 왜 필요한지와 실제로 어떻게 동작하는지를 남기는 것을 목표로 합니다.

## 현황

| 카테고리 | 디렉터리 | 문서 수 |
| --- | --- | --- |
| 운영체제 | [operating-system](operating-system/) | 8 |
| 네트워크 | [network](network/) | 8 |
| 시스템 설계 | [system-design](system-design/) | 4 |
| 데이터베이스 | database/ | 0 |

## 문서 목록

| 날짜 | 분야 | 주제 | 문서 |
| --- | --- | --- | --- |
| 2026-11-09 | OS | 프로세스와 스레드의 개념과 메모리 구조 | [보기](operating-system/2026-11-09-process-thread-memory.md) |
| 2026-11-10 | OS | CPU 스케줄링과 프로세스 상태 전이 | [보기](operating-system/2026-11-10-cpu-scheduling-process-states.md) |
| 2026-11-11 | OS | 컨텍스트 스위칭 메커니즘과 상태 저장/복원 | [보기](operating-system/2026-11-11-context-switching-state-save-restore.md) |
| 2026-11-12 | OS | 동기화와 임계 영역 (상호 배제와 락 메커니즘) | [보기](operating-system/2026-11-12-synchronization-critical-section.md) |
| 2026-11-13 | OS | 교착 상태(Deadlock)의 원인과 4대 조건 | [보기](operating-system/2026-11-13-deadlock-four-conditions.md) |
| 2026-11-14 | OS | 가상 메모리와 페이징(Paging)의 주소 변환과 요구 페이징 | [보기](operating-system/2026-11-14-virtual-memory-paging.md) |
| 2026-11-15 | OS | I/O 모델과 I/O 멀티플렉싱 (select, poll, epoll) | [보기](operating-system/2026-11-15-io-multiplexing-epoll.md) |
| 2026-11-16 | OS | 메모리 계층 구조와 CPU 캐시 지역성 | [보기](operating-system/2026-11-16-memory-hierarchy-cache-locality.md) |
| 2026-11-17 | 네트워크 | TCP vs UDP와 전송 계층 소켓 버퍼 구조 | [보기](network/2026-11-17-tcp-vs-udp-socket-buffer.md) |
| 2026-11-18 | 네트워크 | TCP 3-Way/4-Way 핸드셰이크와 TIME_WAIT | [보기](network/2026-11-18-tcp-handshake-time-wait.md) |
| 2026-11-19 | 네트워크 | HTTP/1.1 · HTTP/2 · HTTP/3(QUIC) 진화와 전송 구조 | [보기](network/2026-11-19-http-versions-quic.md) |
| 2026-11-20 | 네트워크 | DNS 동작 원리와 캐싱 · TTL | [보기](network/2026-11-20-dns-resolution-caching-ttl.md) |
| 2026-11-21 | 네트워크 | 로드 밸런싱(L4 vs L7)과 커넥션 풀링 | [보기](network/2026-11-21-load-balancing-connection-pooling.md) |
| 2026-11-22 | 네트워크 | HTTPS와 TLS 1.3 핸드셰이크 | [보기](network/2026-11-22-https-tls-1-3-handshake.md) |
| 2026-11-23 | 네트워크 | CORS와 Preflight 요청 원리 | [보기](network/2026-11-23-cors-preflight.md) |
| 2026-11-24 | 네트워크 | REST API 설계와 멱등성 · HTTP 상태 코드 | [보기](network/2026-11-24-rest-api-idempotency-status-codes.md) |
| 2026-11-25 | 시스템 설계 | 확장성 기초와 트래픽 추정 (Scale-Up/Out · QPS 산정) | [보기](system-design/2026-11-25-scalability-traffic-estimation.md) |
| 2026-11-26 | 시스템 설계 | 캐시 아키텍처와 일관성 전략 (Cache-Aside · Stampede 방어) | [보기](system-design/2026-11-26-cache-architecture-consistency.md) |
| 2026-11-27 | 시스템 설계 | 데이터베이스 확장과 샤딩 (Read Replica · Shard Key · Consistent Hashing) | [보기](system-design/2026-11-27-database-scaling-sharding.md) |
| 2026-11-28 | 시스템 설계 | 메시지 큐와 비동기 이벤트 파이프라인 (Backpressure · 멱등 컨슈머) | [보기](system-design/2026-11-28-message-queue-async-pipeline.md) |

## 작성 규칙

- 파일명은 `YYYY-MM-DD-주제.md` 형식으로 작성합니다.
- 이미지는 각 디렉터리 하위의 `images/`에 두고 상대 경로로 참조합니다.
- 문서에는 이모지를 사용하지 않습니다.

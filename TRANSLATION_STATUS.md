# 번역 진행 상황

용어 기준은 [TERMINOLOGY.md](TERMINOLOGY.md)를 따릅니다.
번역 전 영문 원문은 `pre-translation-en` 태그에 남아 있습니다 (`git show pre-translation-en:<파일>`).

## 0단계 — 용어 기준

- [x] `glossary.asciidoc`
- [x] `TERMINOLOGY.md`

## 1단계 — 진입 문서

- [x] `README.md` (국문 상단 + 영문 원문 하단)
- [x] `BOOK.md` (완전 교체)
- [x] `preface.adoc`

## 2단계 — 도입부

- [x] `ch01_intro.adoc`
- [x] `ch02_overview.adoc`

## 3단계 — 키·지갑·트랜잭션

- [x] `ch04_keys.adoc`
- [ ] `ch05_wallets.adoc`
- [ ] `ch06_transactions.adoc`

## 4단계 — 나머지 본문

- [ ] `ch03_bitcoin-core.adoc`
- [ ] `ch07_authorization-authentication.adoc`
- [ ] `ch08_signatures.adoc`
- [ ] `ch09_fees.adoc`
- [ ] `ch10_network.adoc`
- [ ] `ch11_blockchain.adoc`
- [ ] `ch12_mining.adoc`
- [ ] `ch13_security.adoc`
- [ ] `ch14_applications.adoc`

## 5단계 — 부록

- [ ] `appa_whitepaper.adoc`
- [ ] `appb_errata.adoc`
- [ ] `appc_bips.adoc`

## 미포함

- `meta/github_contrib.adoc` — 기여자 명단, 수정하지 않음
- `LICENSE`, `atlas.json`, `tools/` — 원문 유지

## 렌더링 검증

`tools/check`는 `asciidoctor`와 `htmlproofer`를 필요로 하며 현재 이 환경에 설치되어 있지 않습니다.
설치 후 아래로 마크업 깨짐을 확인할 수 있습니다.

```
gem install asciidoctor html-proofer && ./tools/check
```

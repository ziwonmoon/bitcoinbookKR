# 번역 용어 대조표

이 문서는 한국어 번역 전체에서 용어를 일관되게 유지하기 위한 기준표입니다.
새 챕터를 번역하기 전에 이 표를 먼저 확인하고, 표에 없는 용어를 결정하면 여기에 추가합니다.

## 표기 원칙

1. **번역하지 않는 것**: 코드, 명령어, 함수·변수·필드명, 16진수 값, 스크립트 예제, 파일 경로, URL, BIP 번호, 오피코드 이름(`OP_RETURN` 등).
2. **용어집 표제어 형식**: `한글(영문 용어)::` — 한글을 앞에 두고 영문을 괄호로 병기합니다. 대응하는 한글이 없는 약어(ECDSA, HTLC, KYC, P2PKH 등)는 영문 그대로 둡니다. 항목 순서는 원문의 영문 알파벳 순서를 그대로 유지합니다.
3. **본문 첫 등장 시**: `한글 용어(English)` 형태로 한 번 병기하고, 이후에는 한글만 사용합니다. 약어(ECDSA, UTXO, HTLC 등)는 그대로 씁니다.
4. **Bitcoin / bitcoin**: 원문은 대문자를 네트워크·프로토콜, 소문자를 화폐 단위에 씁니다. 한국어로는 둘 다 "비트코인"이며 문맥으로 구분합니다. 화폐 단위임을 분명히 해야 할 때만 "비트코인(화폐 단위)" 또는 `BTC`를 씁니다.
5. **문체**: 평서형 `~합니다` 체(원서의 설명 톤에 맞춤). 명령형 지시문은 `~하세요`.
6. **숫자·단위**: 원문 그대로. 소수점·자릿수 구분 기호도 원문 유지.

## 핵심 용어

| English | 한국어 | 비고 |
|---|---|---|
| address | 주소 | |
| block | 블록 | |
| block header | 블록 헤더 | |
| block height | 블록 높이 | |
| block reward | 블록 보상 | |
| blockchain | 블록체인 | |
| coinbase | 코인베이스 | 음역 유지 |
| coinbase transaction | 코인베이스 트랜잭션 | |
| cold storage | 콜드 스토리지 | |
| confirmation | 확인 | "컨펌" 쓰지 않음 |
| consensus | 합의 | |
| consensus rules | 합의 규칙 | |
| difficulty | 난이도 | |
| difficulty retargeting | 난이도 재조정 | |
| difficulty target | 난이도 목표 | |
| double-spending | 이중지불 | |
| encumbrance | 제약 조건 | |
| fee | 수수료 | |
| fork | 포크 | |
| full node | 풀 노드 | |
| genesis block | 제네시스 블록 | |
| hard fork | 하드 포크 | |
| hash | 해시 | |
| hashlock | 해시락 | |
| HD wallet | HD 지갑 | 첫 등장 시 "계층 결정적(HD) 지갑" |
| input | 입력 | 트랜잭션 입력 |
| input script | 입력 스크립트 | |
| locking script | 잠금 스크립트 | |
| lock time | 잠금 시간 | 필드명 `nLockTime`은 원문 유지 |
| mempool | 멤풀 | |
| merkle root / tree | 머클 루트 / 머클 트리 | |
| miner | 채굴자 | |
| mining | 채굴 | |
| multisignature (multisig) | 다중서명 | |
| network | 네트워크 | |
| node | 노드 | |
| nonce | 논스 | |
| opcode | 옵코드 | 개별 옵코드명은 원문 유지 |
| orphan block | 고아 블록 | |
| output | 출력 | 트랜잭션 출력 |
| output script | 출력 스크립트 | |
| paper wallet | 종이 지갑 | |
| payment channel | 결제 채널 | |
| peer-to-peer | P2P | |
| pooled mining | 풀 채굴 | |
| proof of work | 작업증명 | |
| proof of stake | 지분증명 | |
| public key | 공개키 | |
| reward | 보상 | |
| satoshi | 사토시 | |
| Script | 스크립트 | 언어명일 때 대문자 유지 불필요 |
| secret key | 비밀키 | 3판은 private key 대신 secret key를 씀. "개인키"는 쓰지 않음 |
| Segregated Witness (segwit) | 세그윗 | 첫 등장 시 "분리된 증인(Segregated Witness, 세그윗)" |
| soft fork | 소프트 포크 | |
| stale block | 스테일 블록 | 고아 블록과 구분 |
| timelock | 타임락 | |
| transaction | 트랜잭션 | "거래"로 쓰지 않음 |
| unlocking script | 해제 스크립트 | |
| UTXO | UTXO | 첫 등장 시 "미사용 트랜잭션 출력(UTXO)" |
| wallet | 지갑 | |
| witness | 위트니스 | |

## 고유명사

| English | 한국어 |
|---|---|
| Bitcoin Core | 비트코인 코어 |
| Lightning Network | 라이트닝 네트워크 |
| Satoshi Nakamoto | 사토시 나카모토 |
| Byzantine Generals Problem | 비잔틴 장군 문제 |
| Wallet Import Format (WIF) | 지갑 가져오기 형식(WIF) |
| Simplified Payment Verification (SPV) | 단순 지불 검증(SPV) |

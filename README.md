# KISA Phishing URL Dataset

> 한국인터넷진흥원(KISA) 공공데이터포털에서 제공하는 **피싱 사이트 URL 데이터**를 기반으로 한 연구·학습·방어 목적의 데이터셋입니다.

---

## Repository Purpose

이 레포지토리는 다음과 같은 **비악의적 목적**을 위해 만들어졌습니다.

* 피싱 사이트 **탐지 / 차단 로직 연구**
* 보안 교육 및 학습 자료
* URL 분석, 도메인 패턴 연구
* 모바일 / 서버 환경에서의 보안 기능 테스트

❗ **본 레포지토리는 어떠한 악성 행위도 지원하거나 조장하지 않습니다.**

---

## Important Disclaimer

* 본 레포지토리에 포함된 데이터는 **KISA 공공데이터**를 가공한 것입니다.
* 모든 URL 정보는 **사고 방지를 위해 defang 처리**되어 있으며, 실제 접속이 불가능합니다.
* 이 데이터는 **연구, 교육, 방어 목적**으로만 사용해야 합니다.
* 데이터의 최신성, 정확성, 실시간 유효성은 보장되지 않습니다.
* 본 레포지토리의 데이터를 사용함으로 인해 발생하는 모든 책임은 사용자에게 있습니다.

---

## URL Handling Policy (Defanging)

본 레포지토리에서는 GitHub 정책 및 사용자 안전을 위해 **원본 URL을 그대로 공개하지 않습니다**.

### Example

| Original (Not Included)                                | Defanged Version            |
| ------------------------------------------------------ | --------------------------- |
| [https://example.com/login](https://example.com/login) | example[.]com/login         |

또는 다음과 같은 형태로 제공합니다.

* scheme 제거
* domain 단위 분리
* path 분리

---

## Data Source

* **Provider**: Korea Internet & Security Agency (KISA)
* **Platform**: Public Data Portal (data.go.kr)
* **Original Data**: Phishing site detection information

본 데이터셋은 원본 데이터를 **가공·정제**한 2차 저작물입니다.

---

## License

이 레포지토리는 **MIT License**를 따릅니다.

단, 원본 데이터(KISA 공공데이터)는 해당 기관의 이용 조건을 따릅니다.

* 출처 표시 필수
* 악의적 사용 금지

자세한 내용은 `LICENSE` 파일을 참고하세요.

---

## Prohibited Use

다음과 같은 사용은 **명확히 금지**됩니다.

* 실제 피싱 공격 수행
* 악성 코드 또는 공격 도구 제작
* 자동 수집을 통한 재배포 (악성 목적)


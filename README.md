# Japanese-packs

JLPT N1 학습 앱에서 **온디맨드로 내려받는 사전/예문 팩**을 호스팅하는 저장소입니다.
앱 소스는 별도 비공개 저장소에 있으며, 이 저장소에는 배포용 데이터 자산만 둡니다.

앱은 `dictionary_pack_index.json` 을 읽어 각 팩의 `downloadUrl` 에서 zip 을 내려받고,
`sha256` 을 검증한 뒤 설치합니다.

## 팩 목록

| packId | 내용 | 압축 | 설치 후 |
|---|---|---|---|
| `full-jmdict-ko-v1` | JMdict 기반 일본어–한국어 사전 + 한국어 대역 팩 | 약 42 MB | 약 165 MB |

## 라이선스 · 출처

### 사전 데이터 — JMdict / KANJIDIC (EDRDG)

이 팩의 사전 데이터는 **Electronic Dictionary Research and Development Group (EDRDG)** 의
JMdict / KANJIDIC 파일에서 파생되었습니다.

- **라이선스: Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)**
- 저작권자: © Electronic Dictionary Research and Development Group
- 원본 및 라이선스 전문: https://www.edrdg.org/edrdg/licence.html
- JMdict 프로젝트: https://www.edrdg.org/jmdict/j_jmdict.html

**ShareAlike**: 이 팩은 JMdict 의 파생물이므로 **동일하게 CC BY-SA 4.0 으로 배포**됩니다.
이 데이터를 재사용·변형해 배포하는 경우에도 같은(또는 호환되는) 라이선스를 적용해야 합니다.

EDRDG 는 원저작물에 대한 저작권을 보유하며, 본 저장소는 그에 대한 저작권을 주장하지 않습니다.

### 한국어 대역

한국어 뜻풀이는 위 원본 데이터를 가공해 생성한 것으로, 마찬가지로 CC BY-SA 4.0 을 따릅니다.

### 갱신

EDRDG 라이선스가 요구하는 대로, 원본 데이터의 최신판을 반영해 팩을 주기적으로
재생성·배포합니다.

## 앱 내 표시

앱의 **설정 → 사전 출처 / 라이선스** 화면에서 위 출처와 라이선스를 확인할 수 있습니다.

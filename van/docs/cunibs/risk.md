---
icon: '3'
---

# RISK 유형별 처리 방법

{% hint style="info" %}
**※** <mark style="color:red;">**RISK 관리란?**</mark>\
&#x20;    가맹점이 정상적으로 <mark style="color:red;">카드 승인 및 입금</mark> 받을 수 있도록 CUNIBS에 올바른 가맹정보를 등록하고,\
&#x20;    **주기적으로 관리**하는 업무

**※  &#x20;**<mark style="color:red;">**RISK 관리를 하지 않으면?**</mark>\
&#x20;    카드 승인 거절 혹은 승인이 되더라도 입금이 누락되어 가맹점이 <mark style="color:red;">손해를 보게 됨</mark>\
&#x20;    (거래 미청구건은 3개월 뒤 카드사가 <mark style="color:red;">거래 취소</mark>함)
{% endhint %}

***

<figure><img src="../.gitbook/assets/image (129).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><mark style="background-color:blue;"><strong>미등록이란 무엇인가요? 어떻게 처리해야 하나요? [2500]</strong></mark></summary>

* \[2100] 가맹점 등록 수정에 9개 카드사 중 하나의 카드사라도 가맹점번호가 등록되지 않은 경우를 뜻합니다.
* \[2500] 미등록 미개시 화면에서 조회 구분을 "미등록" 으로 놓고 조회하시면 해당 가맹점을 확인하실 수 있습니다.

<figure><img src="../.gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure>

* \[2100]가맹점 원장에 가맹번호를 등록하지 않은 카드사로 승인을 시도하시면 "미등록가맹점"으로 승인 거절되거나 공동승인이 발생합니다

***

처리방법

* 가맹번호 확인 후 가맹점 원장에 등록하시면 됩니다. (카드사 홈페이지 or ARS로 확인했을 때 가맹번호가 없거나 해지되어있으면 BIZFast 신규 진행해주세요)

<figure><img src="../.gitbook/assets/image (145).png" alt=""><figcaption></figcaption></figure>

* 해당 카드사의 카드를 받기 원치 않으신다면 NVAN - 가맹점관리 - 공동망 승인거절 확약서 접수해주세요

</details>

<details>

<summary><mark style="background-color:blue;"><strong>미개시란 무엇인가요? 어떻게 처리해야 하나요? [2500]</strong></mark></summary>

* \[2100] 가맹점 등록 수정에 9개 카드사 중 하나의 카드사라도 자동이체를 개시하지 않은 경우를 뜻합니다. (자동이체를 개시하지 않으면 전표를 직접 매입사에 제출해야 입금됨!!!)
* \[2500] 미등록 미개시 화면에서 조회 구분을 "미개시" 로 놓고 조회하시면 해당 가맹점을 확인하실 수 있습니다.

<figure><img src="../.gitbook/assets/image (146).png" alt=""><figcaption></figcaption></figure>

***

<mark style="color:blue;">처리방법</mark>

* 발견하시는 즉시 \[2100]가맹점 등록수정에 "자동이체 일괄개시" 버튼을 눌러 자동이체를 개시해주세요

<figure><img src="../.gitbook/assets/image (147).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="background-color:blue;"><strong>개시전거래란 무엇인가요? 어떻게 처리해야 하나요? [4100]</strong></mark></summary>

* \[2100] 가맹점 등록 수정에 카드사 가맹번호 자동이체를 개시하지 않은 상태에서(=미개시) 발생한 거래입니다.

***

<mark style="color:blue;">처리방법</mark>

* \[2100] 가맹점 원장 하단 카드사 가맹번호 오른쪽에 "자동이체 일괄개시" 버튼을 눌러 개시하시고, 익영업일에 \[4100]통합매입누락관리에서 조회 하신 후 청구처리 해주세요 <mark style="color:red;">**(익 영업일이 되어야 처리 가능함!!)**</mark>

</details>

<details>

<summary><mark style="background-color:blue;"><strong>자동이체개시해지반송이란 무엇인가요? 어떻게 처리해야 하나요? [4200]</strong></mark></summary>

* \[2100]가맹점 등록수정에서 가맹번호를 등록하고 자동이체를 개시했으나 카드사와 정보가 달라 개시가 해지되는 경우입니다. (주로 카드사가 가맹점 무실적)
* \[4200] 자동이체 개시해지 결과조회 화면에서 조회하실 수 있습니다.

<figure><img src="../.gitbook/assets/image (148).png" alt=""><figcaption></figcaption></figure>

***

<mark style="color:blue;">처리방법</mark>

* <mark style="color:blue;">처리방법 R6</mark>: 해지 정지중인 가맹점: 카드사로 가맹점 상태 정상여부 카드사로 확인 후 재개시 (무실적, 폐업 등으로 가맹번호가 해지되는 경우 有)
* <mark style="color:blue;">처리방법 RA</mark>: BC카드의 경우 9로 시작하는 가맹번호는 임시번호이므로 7로 시작하는 가맹번호로 등록/ 폐업 등으로 인하여 VAN 계약을 해지한 가맹점의 경우 CAT-ID 해지 및 단말기 회수
* <mark style="color:blue;">처리방법 RJ</mark>: DESC 가맹점(서명패드 설치 가맹점)을 \[2100]가맹점 정보등록수정 화면에서 DDC로 개시했을때 발생. 서명패드 설치 가맹점의 경우 DESC로 자동이체 일괄개시

<figure><img src="../.gitbook/assets/image (149).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="background-color:blue;"><strong>중복승인이란 무엇인가요? 어떻게 처리해야 하나요? [4100]</strong></mark></summary>

* 동일 가맹점에서 동일 카드로 동일금액, 끝자리틀린금액, 단위틀린금액으로 발생된 거래 중 정상거래 확률이 높은 마지막 거래 1건은 전송하고 앞 거래는 모두 보류됩니다. (23.03.21 정책 변경으로 전자서명된 거래는 무조건 청구되고, DDC 거래는 5만원 초과건에 대해서만 중복승인으로 잡혀서 별도처리 필요)
* 전자서명 되지 않은 거래의 경우, 5만원 초과 금액은 ① 5분 이내 동일 카드 동일 금액 ② 2시간 이내 동일 카드 0단위 다른 금액일 때 중복승인으로 잡힙니다.

<figure><img src="../.gitbook/assets/image (150).png" alt=""><figcaption></figcaption></figure>

***

<mark style="color:blue;">처리방법</mark>

* \[4100] 통합매입누락관리 화면에서 보류된 건의 정상 유/무를 확인하여 처리하여야 합니다.
* 중복승인건 정상 여부는 먼저 가맹점으로 확인 후 정상건일 경우 <mark style="color:red;">**청구**</mark>, 아닐 경우 <mark style="color:red;">**보류처리.**</mark>
* 보류한 거래가 체크카드이거나 금액이 커서 고객 민원이 예상되는 경우, 카드사나 단말기를 통하여 취소하여야 합니다.

<figure><img src="../.gitbook/assets/image (151).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="background-color:blue;"><strong>공동승인이란 무엇인가요? 어떻게 처리해야 하나요? [4100]</strong></mark></summary>

* 특정 카드사의 가맹번호가 정상 상태가 아닐 때, (\[2100]가맹점 등록수정에 가맹번호가 미등록 or 해지 되어있거나 카드사에서 자체적으로 가맹번호를 해지한 경우) 해당 카드사에 공동승인 가능 가맹점으로 등록되어 있을 경우 D+2\~3일부터 공동승인이 발생합니다
* 별도의 청구 절차를 거쳐야만 입금을 받을 수 있습니다.

<figure><img src="../.gitbook/assets/image (152).png" alt=""><figcaption></figcaption></figure>

***

<mark style="color:blue;">처리방법</mark>

* <mark style="color:blue;">처리방법 1. (가맹점 번호를 받을 수 없는 상황이라면) 전표를 BC 카드로 직접 매입</mark>
* 5만원 미만 거래 보관전표& 거래전표 출력 "비정상매출표 접수 확인서" 작성 매입
* 5만원 이상 거래 보관전표& 서명, 거래전표 출력 "비정상매출표 접수 확인서+확약서(카드사에서 받음)" 작성 매입
* <mark style="color:blue;">처리방법 2.</mark>&#x20;

&#x20;     정상 가맹번호를 \[2100]가맹점 등록수정에 등록, 자동이체 개시한 후 익 영업일에 \[4100] 통합매입누락관리에서 청구처리

* 입금 누락 등의 사유로 원치 않을 시 NVAN - 가맹점관리 - 공동망 승인거절 확약서 접수해주세요 (단, 삼성카드의 경우 별도의 자체망을 쓰기 때문에 공동승인여부가 \[N]이라도 공동승인 되는 경우가 드물게 있습니다.)

<figure><img src="../.gitbook/assets/image (153).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (154).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="background-color:blue;"><strong>매입반송이란 무엇인가요? 어떻게 처리해야 하나요? [4110]</strong></mark></summary>

* 거래를 청구했으나 카드사에서 어떠한 사유로 인하여 반송한 거래입니다
* \[4110]매입반송관리에서 조회 하실 수 있습니다\
  (조회방법: 청구일자-최근3개월까지/처리대상-처리대상(중요!)/처리상태-미처리/나머지-기본값)

<figure><img src="../.gitbook/assets/image (155).png" alt=""><figcaption></figcaption></figure>

***

<mark style="color:blue;">사유별 처리방법</mark>

* <mark style="color:blue;">① 매입불가/해지/정지중인 가맹점</mark>&#x20;

&#x20;       **- 처리방법1:** 가맹점번호 정상여부 확인 후 재개시, 익 영업일에 \[4110]에서 \[수정]→\[등록]\
&#x20;         ※\[재청구] 버튼은 기존 가맹번호로 카드사에 청구됨&#x20;

&#x20;       **- 처리방법2:** 가맹점번호 정상여부 확인 후 전표를 카드사로 매입

* <mark style="color:blue;">② 제시기일 경과:</mark>&#x20;

&#x20;        매입사로 전표 매입 (해외카드는 제시기일 최소5일이므로 카드사에서 처리 안해줄 수도 있음)

* <mark style="color:red;">※</mark> <mark style="color:red;"></mark><mark style="color:red;">**처리 제외건은 처리가 필요 없는 건**</mark>입니다. 조회 시 처리대상을 꼭 처리대상으로 놓아주세요

<figure><img src="../.gitbook/assets/image (158).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="background-color:blue;"><strong>전화승인이란 무엇인가요? 어떻게 처리해야 하나요? [4100]</strong></mark></summary>

* 전화승인이란 단말기 고장이나 통신에러, 카드 손상 등의 사유로 카드사에 전화를 걸어 ars 승인을 받는 방법입니다

***

<mark style="color:blue;">처리방법</mark>

* 압인→ 승인 → 청구
* <mark style="color:blue;">①</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**압인전표 작성**</mark> (매입사에서 전표 양식 제공)&#x20;

&#x20;     <mark style="color:blue;">②</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**승인**</mark>**:** 카드사에 전화하여 ARS로 8자리 승인번호 받기 (압인전표에 기재)&#x20;

&#x20;     <mark style="color:blue;">③</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**청구**</mark>**:** 압인전표를 매입사로 제출. 단, 각 지점별로 매입업무 수행 여부를 전화로 반드시 확인 후 방문

<figure><img src="../.gitbook/assets/image (160).png" alt=""><figcaption></figcaption></figure>

</details>


# 1. Couchbase Capella 클러스터 생성

## 계정 생성

계정을 생성하려면 [Couchbase Capella 가입(Sign-up)페이지](https://cloud.couchbase.com/sign-up)로 이동합니다.

<figure><img src=".gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>



#### 1) 가입 방식 선택을 선택합니다.

* GitHub 또는 Google 계정으로 가입하거나,
* 이메일과 비밀번호를 입력해 직접 가입할 수 있습니다.

#### 2) 가입 정보를 입력합니다.

* 전체 이름 (Full Name)
* 이메일 주소 (Email Address)
* 비밀번호 (Password) → 다음 조건 충족 필요
  * 최소 8자 이상
  * 대문자(A-Z) 포함
  * 소문자(a-z) 포함
  * 숫자(0-9) 포함
  * 특수문자(@, #, $, 등) 포함

\
3\) 약관을 검토 및 동의 과정이 필요합니다 (필수)

*   “I agree to the Terms of Use (including the relevant product supplement) and the Privacy Policy.”

    &#x20;이 체크박스에 반드시 체크해야 **`Get Started`**&#xBC84;튼이 활성화됩니다.

\
4\) (선택 사항) 프로모션 구독

*   “I agree to be updated on offers, products, and services from Couchbase.”

    &#x20;Couchbase의 제품/서비스 관련 소식을 받고 싶을 때만 체크 (선택사항).

\
5\) Get Started를 클릭합니다.

* 버튼을 누르면, 입력한 이메일 주소로 계정 확인용 인증 코드가 전송됩니다.

{% hint style="danger" %}
이메일이 받은 편지함에 보이지 않을 경우, 스팸함(Spam/Junk Mail) 으로 분류되었을 수 있으니 반드시 스팸함도 함께 확인하시기 바랍니다.
{% endhint %}

\
6\) 이메일 인증을 합니다.

* 받은 이메일에 포함된 **확인 코드(confirmation code)**&#xB97C; 입력창에 입력합니다.

<figure><img src=".gitbook/assets/image (16).png" alt="" width="375"><figcaption></figcaption></figure>

\
7\) **확인 코드(confirmation code)**&#xB97C; 입력하고 잠시 기다리시면 계정 생성이 완료되며, Capella에 로그인됩니다.

<figure><img src=".gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>





## 첫 번째 운영 클러스터 생성 및 배포

1\) 계정 생성 후 처음으로 보시는 화면은 클러스터의 프로젝트로 My First Project가 선택되어 있는 상태입니다. 여기서 `Create Cluster`를 클릭합니다.

<figure><img src=".gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>



2\) Cluster Option에서 Free를 선택합니다.

3\) Name 입력란에 클러스터 이름을 입력하거나 기본값을 그대로 사용합니다.

5\) (선택 사항) 클러스터에 대한 설명을 입력합니다.

6\) 사용 가능한 클라우드 서비스 제공업체 중 하나를 선택합니다:

* AWS
* Google Cloud
* Azure

7\) 클러스터의 사용 가능한 지리적 리전을 선택합니다.

8\) 클러스터의 CIDR Block을 입력하거나 기본값을 그대로 사용합니다.

* CIDR 블록 구성 방법에 대한 자세한 내용은 _Cloud Service Provider, Region, and CIDR Bloc&#x6B;_&#xC744; 참조하세요.

9\) Create Cluster를 클릭하여 Capella에서 무료 티어 운영 클러스터를 배포합니다.

<figure><img src=".gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>



10\) 클러스터가 배포 중(Deploying)인 것을 확인하실 수 있습니다. 배포 완료까지는 수 분이 소요됩니다.

<figure><img src=".gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>




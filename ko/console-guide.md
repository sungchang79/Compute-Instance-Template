## Compute > Instance Template > 콘솔 사용 가이드

### 인스턴스 템플릿 생성
인스턴스 템플릿을 작성할 때 필요한 항목은 다음과 같습니다.

<table class="it">
  <tr>
    <th>분류</th>
    <th>항목</th>
    <th>설명</th>
  </tr>
  <tr>
    <td rowspan="2">템플릿 정보</td>
    <td>이름</td>
    <td>인스턴스 템플릿의 이름</td>
  </tr>
  <tr>
    <td>설명</td>
    <td>인스턴스 템플릿의 설명, 영문자 기준 최대 255자</td>
  </tr>
  <tr>
    <td rowspan="7">인스턴스 정보</td>
    <td>이미지</td>
    <td>생성할 인스턴스의 운영체제 이미지</td>
  </tr>
  <tr>
    <td>가용성 영역</td>
    <td>인스턴스가 생성될 영역</td>
  </tr>
  <tr>
    <td>인스턴스 이름</td>
    <td>생성할 인스턴스의 이름</td>
  </tr>
  <tr>
    <td>인스턴스 타입</td>
    <td>생성할 인스턴스의 사양</td>
  </tr>
  <tr>
    <td>키 페어</td>
    <td>생성할 인스턴스에 접근하기 위한 키</td>
  </tr>  
  <tr>
    <td>블록 스토리지 타입</td>
    <td>생성할 인스턴스의 기본 디스크 종류</td>
  </tr>
  <tr>
    <td>블록 스토리지 크기(GB)</td>
    <td>생성할 인스턴스의 기본 디스크 크기<br>인스턴스의 사양에 따라 크기가 제한됨</td>
  </tr>
  <tr>
    <td rowspan="3">네트워크 정보</td>
    <td>네트워크</td>
    <td>생성할 인스턴스에 연결할 네트워크<br>여러 개의 네트워크를 연결한다면 첫 번째 네트워크가 기본 게이트웨이 주소로 설정됨</td>
  </tr>
  <tr>
    <td>플로팅 IP</td>
    <td>생성할 인스턴스에 플로팅 IP 할당 여부</td>
  </tr>
  <tr>
    <td>보안 그룹</td>
    <td>생성할 인스턴스의 보안 규칙</td>
  </tr>
  <tr>
    <td rowspan="2">추가 정보</td>
    <td>추가 블록 스토리지</td>
    <td>생성될 인스턴스에 추가적으로 할당할 디스크의 이름, 타입, 크기를 설정</td>
  </tr>   
  <tr>
    <td>예약 스크립트</td>
    <td>생성될 인스턴스에서 부팅 직후 실행할 스크립트</td>
  </tr>
</table>

> [참고]
> 추가 블록 스토리지는 예약 스크립트를 통해 마운트 과정을 거쳐야 사용할 수 있습니다. 예약 스크립트를 통한 마운트 과정은 [블록 스토리지 가이드](/Storage/Block%20Storage/ko/overview/#_2)를 참고하시기 바랍니다.

<br/>

> [주의]
> 인스턴스 템플릿은 한번 생성하면 수정할 수 없습니다.

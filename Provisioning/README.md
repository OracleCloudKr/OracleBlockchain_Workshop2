# 오라클 블록체인 인스턴스 생성하기
이 단계에서는 3개의 블록체인 인스턴스를 생성할 예정입니다. Founder 인스턴스 1개와 Participant 인스턴스 2개를 생성하게 됩니다. 인스턴스의 Role은 Founder와 Participant 두가지로 선택이 가능합니다. Founder는 블록체인 네트워크의 중심이 되는 인스턴스로 다른 여러 Participant 인스턴스를 관리할 수 있게 됩니다.

먼저 Oracle Cloud Console에서 블록체인 플랫폼 서비스로 이동합니다.
1. Oracle Cloud에 접속한 후 좌측 상단에 있는 메뉴 버튼을 누른 후 왼쪽 메뉴중에서 '플랫폼 서비스'를 선택 한 후 Blockchain Platform 메뉴를 클릭합니다. 만약 이 메뉴가 보이지 않을 경우 해당 cloud account 의 관리자 계정으로 접속하거나 권한을 별도로 부여 받아야 합니다.
   ![](images/goto_blockchain1.png)
   

2. 블록체인 플랫폼 콘솔에 처음 접속을 한 경우에는 아래와 같이 나오게 됩니다.  
오른쪽에 있는 인스턴스 생성 버튼을 누릅니다.
![](images/goto_blockchain2.png)

3. 이 Lab에서 사용할 블록체인 인스턴스를 만들도록 하겠습니다. 인스턴스 이름을 DetroitAuto로 입력합니다. Founder로 선택해서 인스턴스를 만들겠습니다. Region은 us-ashburn-1 로 선택하겠습니다.
'다음' 버튼을 누릅니다.
![](images/prov1.png)
4. 생성 버튼을 누릅니다.
![](images/prov2.png)

5. 정상적으로 요청이 전달이 되면 인스턴스 생성이 시작됩니다. 인스턴스 생성까지는 수분 정도 소요가 되게 됩니다.
![](images/prov2.png)
6. 이 Lab에서는 3개의 인스턴스를 필요로 하기 때문에 바로 다음 인스턴스들을 생성하도록 하겠습니다. 다시 인스턴스 생성 버튼을 누릅니다.
![](images/prov3.png)
7. 이번에는 SamDealer라는 이름으로 생성하도록 하겠습니다. 주의할 점은 이 인스턴스는 Founder가 아니라 해당 네트워크에 참가하는 Participant로 생성을 하도록 하겠습니다. 'Create a new Network'를 체크 해제 합니다. Region은 'us-ashuburn-1'로 선택합니다.
![](images/prov4.png)

1. SamDealer를 생성하고 바로 JudeDealer라는 이름으로 Participant로 생성합니다. 위와 동일하게 'Create a new Network'를 체크 해제 합니다. Region은 'us-ashuburn-1'로 선택합니다.
![](images/prov5.png)

2. 인스턴스가 생성이 되면 생성이 완료되었다는 메일이 자동으로 발송이 됩니다. 오른쪽에 햄버거 버튼을 클릭하면 해당 인스턴스의 콘솔로 이동할 수 있는 Blockchain Console 이 표시됩니다.
![](images/prov6.png)

1. 새로운 창으로 해당 블록체인 인스턴스를 관리할 수 있는 Dahshboard Console이 열리게 됩니다.
![](images/prov7.png)

1. SamDealer와 JudeDealer의 콘솔을 열어보면 아래와 같이 조금 다른 형태의 화면이 보이게 됩니다. 앞에서 인스턴스를 생성할때 Network를 체크한 Founder의 경우에는 자체적으로 동작하게 되지만, JuderDealer와 SamDealer는 체크를 해제 했습니다. 이는 자체적인 네트워크를 생성하지 않은 Participant로서 반드시 Founder에 Join을 해야만 동작을 합니다. 이 부분은 이후 Lab에서 구성해 보도록 하겠습니다.
![](images/prov8.png)
---
[이전 Lab으로 이동](../README.md)

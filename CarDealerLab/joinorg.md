# Founder에 Participant Join 하기
## A. Founder(DetroitAuto)에 JudeDealer와 SamDealer를 Join하기
1. 인스턴스가 생성이 되면 생성이 완료되었다는 메일이 자동으로 발송이 됩니다. 오른쪽에 햄버거 버튼을 클릭하면 해당 인스턴스의 콘솔로 이동할 수 있는 Blockchain Console 이 표시됩니다.
![](images/prov6.png)

1. 새로운 창으로 해당 블록체인 인스턴스를 관리할 수 있는 Dahshboard Console이 열리게 됩니다.
![](images/prov7.png)

1. SamDealer와 JudeDealer의 콘솔을 열어보면 아래와 같이 조금 다른 형태의 화면이 보이게 됩니다. 앞에서 인스턴스를 생성할때 Network를 체크한 Founder의 경우에는 자체적으로 동작하게 되지만, JuderDealer와 SamDealer는 체크를 해제 했습니다. 이는 자체적인 네트워크를 생성하지 않은 Participant로서 반드시 Founder에 Join을 해야만 동작을 합니다. 
![](images/prov8.png)

1. 중앙에 있는 2번 'Export Certificates' 를 클릭한 후에 오른쪽 하단의 **Export** 버튼을 눌러 **JudeDealer-certificates.json** 파일을 서버로 부터 로컬 컴퓨터에 다운로드 합니다. 이 파일에는 Participant Org의 인증서와 관리하는 피어 노드에 대한 정보가 들어 있습니다.<br/>
![](images/judedealer_join1.png)

1. 다음 단계는 접속하고자 하는 Founder의 Orderer 정보를 import 해야 합니다. **Import Orderer Settings**를 클릭합니다.
![](images/judedealer_join12.png)

4. Blockchain Platform Manager 콘솔에서 DetroitAuto 인스턴스 콘솔에 접속합니다.
![](images/goto_founder.png)

5. **DetroitAuto** Founder 조직의 콘솔로 이동해서 **네트워크** 탭을 선택하십시오. 그런 다음 **DetroitAuto** 조직의 햄버거 메뉴를 클릭하여 Orderer 설정파일을(DetroitAuto-orderer-settings.json) 내보냅니다. 내보낸 파일을 저장하십시오.
![](images/founder_exportorderer.png)

6. 다시 **JudeDealer** 콘솔로 이동해서 **Upload Orderer Settings** 를 클릭합니다. 그리고 앞에서 다운로드 한 **DetroitAuto-orderer-settings.json** 를 선택합니다.
![](images/judedealer_join2.png)

7. 선택한 파일이 정상적으로 upload 되면, 이 파일을 Import를 클릭해서 반영합니다. 마지막으로 Complete 단계를 클릭합니다.
![](images/judedealer_join4.png)

9. JudeDealer의 콘솔 화면의 정보들을 확인할 수 있습니다.
![](images/judedealermain.png)


1. 위와 동일한 방식으로 **SamDealer** Org를 Founder에 추가합니다. SamDealer Console을 엽니다.
![](images/go_samdealer.png)

2. 여기에서도 앞에서 JudeDealer에서 했던 것과 동일하게 수행합니다. 완료가 되면 아래와 같이 보이게 됩니다.
![](images/samdealer_done.png)

3.  이제 Founder인 DetroitAuto콘솔로 이동합니다.
4.  Founder에도 참가자인 **JudeDealer**와 **SamDealer**를 추가해 주어야 합니다. DetroitAuto 콘솔의 Network 탭으로 이동해서 **Add Organizations** 버튼을 클릭합니다.
![](images/founder_addorg.png)

1.  **Upload Organization Certificates** 버튼을 클릭합니다.
![](images/founder_addorg2.png)

11. 앞에서 다운로드 받은 **SamDealer-certificates.json** 파일을 선택합니다.
![](images/founder_addorg4.png)

1. 플러스 버튼을 눌러 **JudeDealer-certificates.json** 파일도 한번에 같이 추가합니다. 이제 **Add** 버튼을 눌러서 등록합니다.
![](images/founder_addorg5.png)

1. 두 개의 Participant가 정상적으로 추가되었습니다.
![](images/founder_addorg6.png)
---
[이전 Lab으로 이동](README.md)

# Perforce 가이드
1. 설치
   1. 사이트에 접속해서 다운 받고 설치한다.
    https://www.perforce.com/downloads/helix-visual-client-p4v
      ![](./images/perforcedown.png)

      ![](./images/install1.png)
   
      ![](/images/install2.png)


   2. 실행해서 ID적고 접속!
  
      ![](./images/signin.png) 


2. 사용법
   1. 초기 세팅
   
      ![](./images/view.png)

   2. Stream생성과 workspace 생성(git의 branch생성 후 연결까지 하는 것과 비슷함)
      
      ![](./images/streamgraph.png)

      ![](./images/createStream.png)
      
      ![](./images/newStream.png)

      ![](./images/completeStream.png)

   3. 위에 적힌 폴더로 가보면 스트림과 연결된 워크스페이스가 있음(메인 브랜치에서 본인 브랜치로 옮겨서 생성된 폴더) 거기에 있는 언리얼 프로젝트 열기
      
      ![](./images/openProject.png)

      ![](./images/openProject2.png)

      ![](./images/openProject3.png)

   4. 언리얼과 퍼포스 연동하기(Content 우측클릭)

      ![](./images/content.png)

      ![](./images/clickSourceControl.png)

   5. 로그인 및 정보 입력하기(워크스페이스를 선택해야 한다.)

      ![](./images/SourceControlLogin.png)

   6. 다음처럼 나온다면 연동 성공!

      ![](./images/ok.png)

   7. 작업하기

      ![](./images/task.png)

   8. 나의 스트림에 submit하기(브랜치 푸시와 유사함) Source Control에서 check out 선택

      ![](./images/checkout.png)

      ![](./images/submit.png)

      ![](./images/submit2.png)

   9. 성공 했다면 퍼포스에서 확인 가능

      ![](./images/perforceworkspace.png)

   10. 내 스트림을 메인 스트림에 머지하기

         ![](./images/merge.png)
      
         ![](./images/merge1.png)

         ![](./images/merge2.png)

         ![](./images/merge3.png)

         ![](./images/merge4.png)


   11. 충돌 처리하기

         ![](./images/conflicts.png)

         ![](./images/resolve.png)




    



참고자료[https://pineoc.github.io/blog/]
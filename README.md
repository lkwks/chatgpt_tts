# chatgpt_macro

ChatGPT <https://chat.openai.com> 에 접속하면 특정 텍스트를 자동으로 프롬프트에 입력 후 그에 대한 답변을 일단 얻어두는 크롬 확장 프로그램. 

- ChatGPT를 사용할 때, '내가 적은 프롬프트가 문법적으로 옳은지 ChatGPT가 먼저 자동으로 교정해준 후 그 다음에 ChatGPT가 내 프롬프트에 대해 답변' 기능을 추가하고 싶어서 만들어 보았다.

  - 처음에는 DOM에 변화가 발생하면 프롬프트가 자동 입력되도록 구현했으나 잘 작동하지 않는 듯해 현재 형태로 변경했다.

- ChatGPT에서 출력되는 답변을 클릭하면 구글 TTS API에 텍스트를 전송해 이로써 생성된 음성을 재생하는 기능을 추가해보았다. 처음에는 단순히 클릭하면 그 영역이 재생되는 간단한 기능을 구현했으나, 점차 다음과 같은 기능을 추가하게 됐다.

  - 재생/일시정지 버튼 구현
  
  - 드래그한 영역만 선택적으로 재생
  
  - 두 기능 모두 사실 꼭 필요한 기능은 아니지만, 드래그한 텍스트를 js로 다루는 방법이 궁금해서 계속 공부하다가 완성하게 됐다. '이거 하려고 이 정도까지 시간을 들여야 했을까? 너무 가성비가 떨어지지 않나?' 싶은 생각도 있지만, 드래그한 텍스트를 js로 다루는 방법은 오래 전부터 궁금했던 방법이라 그 부분에 대한 호기심을 해소했다는 데서 수확이 있다고 생각한다.

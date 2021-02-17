# Web-ChatBot-Bell-
It can Explain about Words of Standard law from South Korea
- 이것은 대한민국에서 적용되는 법률의 스탠다드 용어들에 대하여 설명하는 챗봇입니다.

# Learning Data
|Title|Contents|From|
|:------:|:---:|:------:|
|Data Name|ChatBot 'Bell'|My Brain|
|Basic Sources From|DeFault ChatBot Data Source|https://github.com/songys/Chatbot_data (송영숙님)|
| 1st Additional Data  |Additional Data Sources for ChatBot system|https://korquad.github.io/ (KorQuAD)|
| 2nd Additional Data  |Legal Terms Data |https://www.data.go.kr/data/15069932/fileData.do (공공데이터 포털)|

# Author
Ian/@Ian (aoa8538@gmail.com)

# Requirement
- 사용된 툴은 다음과 같습니다.<br/>
  - Python 3.7.9
  - Tensorflow 2.4.1
  - konlpy
  - pandas
  - numpy
  - socket.io
  
# Structure
- 웹 형태의 챗봇으로써, CSS와 NODE JS도 같이 사용되었으며, 주력 디자인은 'Bootstrap'을 응용했습니다.<br/>
<br/>
├── QnA:&nbsp;&nbsp;&nbsp;&nbsp; 질문과 답변을 저장하는 디렉토리입니다.<br/>
├── socket.io:&nbsp;&nbsp;&nbsp;&nbsp;웹 소켓 구현을 위해 기본적인 파일들이 저장된 디렉토리입니다.<br/>
├── views:&nbsp;&nbsp;&nbsp;&nbsp; 웹 페이지 구현을 위해 작성된 ejs 데이터 파일이 저장된 디렉토리, 'Web Browser'에 해당합니다.<br/>
├── chatbot.py:&nbsp;&nbsp;&nbsp;&nbsp; 프로그램 실행의 시작과 끝까지, 모든 소스가 작성되어 있는 메인 파일입니다.<br/>
├── ChatBotData.csv:&nbsp;&nbsp;&nbsp;&nbsp; '송경숙'님의 데이터 소스(소스 경로는 상위 'Learning Data' 파트에 명시했습니다.)<br/>
├── index.js:&nbsp;&nbsp;&nbsp;&nbsp; 'Web Server'에 해당하는 js 파일입니다.<br/>
├── RealEstate.csv:&nbsp;&nbsp;&nbsp;&nbsp; 부동산(경,공매)및 생활 법률 용어들이 총괄해서 담겨있는 파일입니다.

# Design
<img src="https://user-images.githubusercontent.com/79067558/108025412-c988e100-7069-11eb-8fbd-6903ef0ee0ce.png" width="60%"><br/>
- 디자인은 상위에 소개된 사진과 같으며, 반드시 'chatbot.py'와 'index.js' 이 두 파일을 모두 실행해주셔야 구동됩니다.<br/>
- 챗봇의 전반적인 구동 방식은 'chatbot.py'파일에 수록해놓았으니 참조 바랍니다.<br/>
- 또한 웹 구동 방식 및, 디자인 CSS소스를 비롯하여 'views' 디렉토리 내에 있는 'index.ejs'에 입력 및 설명되어 있으니 참고 하시면 되겠습니다.

# Data(Send & Receive) Flow
<img src="https://user-images.githubusercontent.com/79067558/108029757-61d69400-7071-11eb-8a82-4d0d27512b6c.png" width="60%"><br/>
- 파일을 실행시키기에 앞서, 전반적인 데이터들의 상호작용(흐름)에 대하여 작성해본 사진입니다.<br/>
- 이 그림을 참조하신 후, 앞서 상위 카테고리들로부터 설명한 파일들을 구동시키시면 이해가 훨씬 수월해지실 것 같아 작성했습니다.

# Languages
- Node js, JavaScript, CSS, Python 이렇게 4개의 랭귀지로 개발되었습니다.<br/>
- 추가적으로 슬라이드(Wrapper) Animation Effect가 적용되었으니 어떻게 구현이 되었으며 어떤 방식으로 작동되는지는 작성된 ppt파일과 함께 각 파일들을 실행해본 후,<br/>
- 해당 파일마다 어떻게 적용시켰으며 이유는 무엇인지, 또한 해당 파트는 작동 방식 중, 어떤 부분에 해당하는 지 등<br/>
- 자세히 수록해 놓았으니 참조하신 후 실행하시면 훨씬 수행과 이해에 있어 쉽게 받아들이실 수 있다고 조심스레 개인적인 사견을 이렇게 남겨봅니다.

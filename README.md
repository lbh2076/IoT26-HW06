# IoT26-HW06: Car Plate Recognition System with Raspberry Pi and Node-RED

## Objective
Build a car recognition system using a Raspberry Pi, Node-RED, and OpenALPR API to identify car plates based on an image and trigger hardware outputs. 

## Source Code
* **`flows.json`**: Node-RED에서 구성한 전체 데이터 플로우 파일입니다.
* **`Function Node (JavaScript)`**: API가 반환한 JSON 데이터에서 차량 번호판 값을 파싱하고, 타겟 번호판(예: "sam123")과 일치할 경우 1(LED 켜짐), 아닐 경우 0(LED 꺼짐)을 출력하도록 인가/비인가 로직을 처리하는 코드입니다.

## Results
Node-RED 플로우 구성, API 인식 성공 디버그 화면, 그리고 번호판 인식에 따른 LED 제어 시연 영상(GIF)은 본 저장소에 업로드된 파일을 확인해 주세요.

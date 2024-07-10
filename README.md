# Interlude Drone Project

본 프로젝트는 **Mavlink 프로토콜의 취약점을 분석**하고, **패킷암호화** 제안 및 **성능비교**를 진행한다.
- PX4-Autopilot, QgroundControl, Gazebo를 통해 Mavlink 패킷을 송수신하는 가상드론환경을 세팅
- 가상드론과 가상지상국의 통신 중에 패킷을 캡처하여 페이로드 취약점 분석 및 공격을 수행
- 이후, Mavlink 메시지를 AES-128과 Chacha20을 통해 페이로드 암호화를 진행하고 이에 대한 검증 및 성능을 비교


<img src=https://github.com/8hojung24/Mavlink_Payload_Cryptography/assets/67528774/02aa951b-f3a3-4bad-8475-8895e174093d width='600'>
<br/>
<img src=https://github.com/8hojung24/Mavlink_Payload_Cryptography/assets/67528774/0098c123-9b1b-4622-9cfc-af0952aa190b width='600'>

## 가상드론환경 시현 영상
<a href="https://youtu.be/Hp8-U-EbAGs">
  <img src="http://img.youtube.com/vi/Hp8-U-EbAGs/0.jpg" width="600">
</a>

## 총정리
https://www.notion.so/yuu-jeong/e29fdb04b43144b8a3855dd870760804

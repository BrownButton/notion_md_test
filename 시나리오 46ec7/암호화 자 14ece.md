# 암호화 장비 통신 시나리오

### 개요

암호화 장비를 통해 중앙제어서버와 통신하기 위한 시나리오

### 시나리오

1. LWIP를 이용하여 암호화장비에 (TCP/UDP) 방식으로 정해진 프로토콜을 보내 송수신 통신한다.

### ...

1. TMS570 Hercules 보드에서 간단한 LWIP 예제코드만 돌려봐서 아직 어떤식으로 구성하여 처리할지 생각해봐야한다.
    1. “어떤식으로 구성” 이 부분에 대한 정확한 기능 정의가 필요하다.
2. LWIP를 RTOS 환경에서 사용해서 만약 프로젝트가 nonOS 환경이라면 어떤식으로 처리해야될지 생각해 봐야한다.
    1. 만약 nonOS 환경이라면, DMA로 수신받을 버퍼의 사이즈를 키워놓는 방식으로 처리하면 되지않을까 생각해보았다.
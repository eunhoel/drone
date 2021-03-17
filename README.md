# drone

### 드론 구성품
```
1. 프레임 frame
2. 전원분배장치 Power distribution board PDB
3. 범용전압강화회로 universal battery eliminator circuit UBEC
4. 비행제어장치 Flight controller FC
5. 전자속도제어장치 Electronic speed controller ESC (변속기)
6. 모터 motor
7. 모니터 송 수신기 Radio transmetter receiver
8. 배터리 Battery
9. 프로펠러 Propeller
```
```
1. 프레임 : 드론의 뼈대가 되는 형태
4. FC : 드론을 컨트롤하는 메인 부품
5. 변속기 : 컨트롤러에 의해 모터의 속도를 제어하는 부품 (4개 필요)
6. 모터 : 동력 부품 (4개 필요)
7. 송 수신기 : 무선으로 조정하기 위한 기기
8. 배터리 : 드론 주전우너 공급부품

```
추가적으로는 
```
GPS
Telemetry
Lipo Alarm
Landing Skid
OSDA
```
## Frame
450 mm Quad X model
1045 규격 프로펠러
무게 282G 이륙중량 0.8~1.6KG

ShareGood F450 drone Frame
```
Price : $20
Come with M2.5*8 Screws for assembling
Frame arm size: 21.5 * 3.8 * 5cm / 8.5 * 1.6 * 2.0inch
Weight: 270g
https://www.amazon.com/ShareGoo-Airframe-FrameWheel-Quadcopter-Aircraft/dp/B07H3WDSX3/ref=sr_1_48?dchild=1&keywords=quad+x+f450+frame&qid=1615938244&sr=8-48
```
YoungRC F450 Drone Frame
```
Price : $20
Width: 450mm
Height: 55mm
Weight: 280g (w/out electronics)
Motor Mount Bolt Holes: 16/19mm
G.Weight: 395g
Wheelbase: 17.7in/450mm
Net weight: 272g
https://www.amazon.com/YoungRC-4-Axis-Airframe-Quadcopter Landing/dp/B0776WLHX7/ref=psdc_11608080011_t1_B07H3WDSX3
```
내용이 더 상세하게 설명되어 있는 YoungRC걸 염두해두고 있다. 솔직히 두 개에 차이점을 잘 모르겠다

### Aduino 아두이노 보드 성능 비교표

```
1. Processor : 정보처리하는 요소나 장치, 명령어와 데이터를 처리하는 하드웨어 부품 (CPU)
2. Operating Voltage : 자동/입력 전압
3. Analog in/out :센서 또는 모듈을 아두이노에 연결하여 사용할 때 필요한 핀
```

지이로센서 : 물체의 회전속도인 각속도의 값을 이용하는 센서.
콜리올리 힘 (Coriolis Force)을 전기적 신호로 변환 가능

### FC 아두이노 보드
저자는 아두이노를 보드을 이용한다.
종류로는 
```
1. 프로미니
2. 우노
3. 나노
```
포로미니 같은 경우에는 소형이라는 장점이 있는 데신 USB 연결 장치가 없다.
우노는 사이즈가 크지만 USB 연결 장치가 있다.
브레드보드 필요 (선 정리 무남땜 장치)

### Motor
power가 필요해서 대략적인 드론에 무게를 알아야한다. 나중에 정하도록 하자.

### ESC 변속기
#### 이거는 모터의 전원공급 규격과 동일한 규격이어야한다.
무터 공급 전원이 4Cell인데 ESC의 공급전원이 3Cell이면 모터와 ESC간에 전원공급이 매칭되지 않기 때문에 사용 불가하다.
UBEC와 BEC 타입이 

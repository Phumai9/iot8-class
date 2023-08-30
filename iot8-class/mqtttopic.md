## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"weight": "2"}
        - {"matherial-detection": "1"}
        - {"noise": "2.5"}
        - {"CO2-level": "5"}
        - {"water-level": "3"}
        - {"humudity": "60"}
        - {"lode": "5"}
        - {"time": "20"}


 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"door-contact": "0"}
        - {"humunity": "20"}
        - {"monitor": "1"}
        - {"bluetooth": "1"}
        - {"wifi": "1"}
        - {"remote-management": "1"}
        - {"air-pressure": "210"}
        - {"current": "121"}
        - {vibration": "0.2"}





openapi: 3.0.0
info:
  title: RipplePay API Documentation
  description: |
    ## 🏦 소상공인을 위한 간편 결제 및 환전 서비스, RipplePay

    RipplePay는 소상공인들이 겪는 **환전 수수료 부담**을 덜어주는 혁신적인 솔루션입니다.
    이 앱을 통해 소상공인은 고객과 **QR 코드**로 간편하게 결제를 주고받을 수 있으며,
    결제된 금액은 즉시 **스테이블 코인**으로 환전되어 서로 거래할 수 있습니다.
    
    ### 주요 특징
    * **수수료 절감**: 기존 환전 절차에서 발생하는 높은 수수료를 최소화합니다.
    * **간편한 QR 결제**: 복잡한 과정 없이 QR 코드로 즉시 결제가 가능합니다.
    * **스테이블 코인 활용**: 가격 변동성이 낮은 스테이블 코인을 사용하여 안정적인 거래를 지원합니다.
  version: 1.0.0
servers:
  - url: http://122.40.46.59
    description: Production Server

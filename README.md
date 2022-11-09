# 数字证书验证点
- ## 极客邦数字证书系统

  - ### [根证书 - RSA-4096-SHA](CA.cer)

    > - **证书信息**
    >
    >   - Description = 四川大学智能感知与先进控制实验室
    >
    >   - Description = Intelligent Perception and Advanced Control Lab., SCU
    >
    >   - Description = 四川大学极客邦
    >
    >   - Description = GeekBang of Sichuan University
    >
    >   - CN = SCU GeekBang Root CA, OU = Certificate Management
    >
    >   - O = SCU GeekBang, L = Chengdu, S = Sichuan, C = CN
    >
    > - **[吊销列表](CRL/CA.crl)**

  - #### [中间证书 - SCU GeekBang Tunnel Sub CA](TSC.cer)

    > - **证书信息**
    >
    >   - Description = GeekBang Network Tunnel Root Certificate
    >
    >   - Description = 极客邦网络隧道根证书
    >
    >   - CN = SCU GeekBang Tunnel Sub CA, OU = Network Management
    >
    >   - O = SCU GeekBang, L = Chengdu, S = Sichuan, C = CN
    >
    > - **[吊销列表](CRL/TSC.crl)**

    - ##### [服务证书 - SCU GeekBang MainRouter VPN Server](MR-VPNS.cer)

      > - **证书信息**
      >
      >   - CN = SCU GeekBang MainRouter VPN Server
      >
      >   - OU = Network Management, O = SCU GeekBang
      >
      >   - L = Chengdu, S = Sichuan, C = CN
      >
      > - **[吊销列表](CRL/MR-VPNS.crl)**

    - 

  - ### [根证书 - SM2-E256-SM3](CA-SM2.cer)

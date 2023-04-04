# Amazon VPC
Amazon Virtual Private Cloud(Amazon VPC)를 이용하면 사용자가 정의한 가상 네트워크로 AWS 리소스를 시작할 수 있습니다. 이 가상 네트워크는 AWS의 확장 가능한 인프라를 사용한다는 이점과 함께 고객의 자체 데이터 센터에서 운영하는 기존 네트워크와 매우 유사합니다.
## 항목
1. [VPC](#virtual-private-cloud-vpc)
2. [Subnet](#subnet)
## Virtual Private Clouds (VPC)
  - VPC는 AWS에서 서비스하는 가상네트워크 집합이다.
  - 각 리전에 독립적인 VPC를 구성하여 각 AWS 서비스들을 독립적인 개인 네트워크에서 통신을 할 수 있다.  

## Subnets
- 

## IP Addressing
- 

## Routing
- VPC와 서브넷에 IPv4 주소와 IPv6 주소를 할당할 수 있습니다. 또한 퍼블릭 IPv4 및 IPv6 GUA 주소를 AWS로 가져오고 VPC의 리소스(예: EC2 인스턴스, NAT 게이트웨이, Network Load Balancer)에 할당할 수 있습니다.

## Gateways and Endpoints
- 

## Peering Connections
- 

## Traffic Mirroring
- 

## Transit Gateways
- 

## VPC Flow Logs
- 

## VPN connections
- 

## VPC 요금
- VPC 사용에 따르는 추가 요금은 없습니다. NAT 게이트웨이, IP 주소 관리자, 트래픽 미러링, Reachability Analyzer, Network Access Analyzer와 같은 일부 VPC 구성 요소에 대해 요금이 부과됩니다. 자세한 내용은 [Amazon VPC](http://aws.amazon.com/vpc/pricing/) 요금을 참조하세요.


### 참고: [Amazon VPC](https://docs.aws.amazon.com/ko_kr/vpc/latest/userguide/what-is-amazon-vpc.html)
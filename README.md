* resource : 쓰기 위한 
* data Source :  읽기 위한

* 명령어
* aws 설정 확인 : aws sts get-caller-identity

* 처음 실행 시 초기화 : terraform init
* 플랜 : terraform plan
* 실행 : terraform apply
* 삭제 : terraform destroy

provider를 새로 추가하게 되면 terraform init 을 진행해야 함

지우고 싶다면 terraform destroyed 사용

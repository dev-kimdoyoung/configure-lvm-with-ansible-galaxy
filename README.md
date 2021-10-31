# Ansible Galaxy를 사용하여 LVM 구성
## 작업환경
- 앤서블 코어 서버: MAC OS
- 대상서버: CentOS 7.x

## 목적
- 앤서블 겔럭시를 사용하여 Role 기반의 구성관리 자동화를 수행함으로써 인프라 코드의 재사용성을 높이기 위함
- 신규 OS 구성 업무 중 주요하게 수행하는 유저/그룹 생성 및 LVM 구축을 자동화하기 위함

## 사용법(인터넷망)
```bash
$ cd ~/lvm2
$ ansible-playbook -i inventory.yaml main.yml -vvv
```

## 작성자
dev-kimdoyoung@github.com

# my-ansible-playbooks

## ansible 설치

```shell
sudo apt update
sudo apt install ansible -y
```

## ansible 실행

```shell
ansible-playbook XXX.yml
```

## Linux 서버

1. roles/linux/tasks/main.yml 설정
2. 도메인 발급
3. Certbot SSL 발급
4. Certbot Nginx 설정
5. 서비스(어플리케이션) 등록
6. 서비스(어드민) 등록

## Docker 서버

1. roles/docker/tasks/main.yml 설정

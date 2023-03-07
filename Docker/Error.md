# 오류 내용
Docker를 이용하여 OS 띄웠을 때 아래와 같은 오류가 발생하는 경우
> failed to get d-bus connection operation not permitted

해결 방법 (예시)
> docker run --privileged -d --name centos centos:latest /sbin/init



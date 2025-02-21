## 1일차 : MongoDB K8s 구축
| 키 | 값 |
|----------|----------|
| Pod 이름   | mongodb   |
| Pod Label  | app: mongo   |
| Container 이름   | mongodb   |
| Container 이미지  | mongo:4   |
| ReplicaSet  | 1   |


## 2일차: 웹 어플리케이션 배포 ( vote-app.yml )
### 아키텍처
![image](https://github.com/user-attachments/assets/60b46037-b3b3-41ec-9e38-6d498c16ea48)

출처  https://subicura.com/k8s/guide/sample.html#%E1%84%8B%E1%85%AF%E1%84%83%E1%85%B3%E1%84%91%E1%85%B3%E1%84%85%E1%85%A6%E1%84%89%E1%85%B3-%E1%84%87%E1%85%A2%E1%84%91%E1%85%A9


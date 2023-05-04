# Jenkins

## How to get pw

```sh
# if "jenkins" is the container name (`docker ps` to check) then:
docker exec jenkins  cat /var/jenkins_home/secrets/initialAdminPassword
```
# Build and Run

```bash
docker build -t helloflask .
docker run -p 9000:5000 --name mikescoolapp -t helloflask 
```
---

# Create a repository
[Create Repository](https://cloud.docker.com/repository/create)

---
# push local image to repository
```sh
docker login

docker tag helloflask [☢️️name of registry☢️]:v1
docker push [☢️️name of registry☢️]:v1
```
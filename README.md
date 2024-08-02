## Dev instructions

#### Docker image
Build: `docker build -t mock-app .`
Run: `docker run -i -p 8080:8080 mock-app`
Tag & Push:
- `docker tag mock-app adamthorpe2/mock-app`
- `docker push adamthorpe2/mock-app`

# react-todo
```
docker image build -t react:v1 .
docker container run -dt --name react_dev -p 3000:3000 -v $(pwd):/code react:v1
docker container exec -it react_dev /bin/bash
cd my-app
npm start
```

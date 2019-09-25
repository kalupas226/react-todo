# react-calculator
```
docker image build -t react:v1 .
docker container run -dt --name react_todo_dev -p 3000:3000 -v $(pwd):/code react:v1
docker container exec -it react_todo_dev /bin/bash
cd todo
npm start
```

构建镜像：
docker build -t flask_plotly:1.1.1

启动容器：
docker run --rm -d -p 10000:5000 flask_plotly:1.1.1

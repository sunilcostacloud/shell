<!-- to build docker image -->

docker build -t shell-image .

<!-- to convert docker image into tar -->

docker save -o shellimage.tar shell-image

<!-- to run in pc -->

docker run -p 8080:8080 shell-image

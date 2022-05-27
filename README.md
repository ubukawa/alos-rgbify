# alos-rgbify
Test of rgbifying ALOS DEM

# unvt/rgbify
git clone https://github.com/unvt/rgbify
cd rgbify
docker build -t unvt/rgbify .
cd ..

docker run -it --rm -v ${PWD}:/data unvt/rgbify
cd /data

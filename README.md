# Cerealis

docker run -it --rm -e "UNITY_USERNAME=287ilias@gmail.com" -e "UNITY_PASSWORD=Mfu08vjv" -e "TEST_PLATFORM=android" -e "WORKDIR=/root/project" -v "$(pwd):/root/project" gableroux/unity3d:2019.2.11f1 bash

xvfb-run --auto-servernum --server-args='-screen 0 640x480x24' /opt/Unity/Editor/Unity -logFile -batchmode -username "287ilias@gmail.com" -password "Mfu08vjv"
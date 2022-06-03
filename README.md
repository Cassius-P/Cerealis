# Cerealis

## Title


xvfb-run --auto-servernum --server-args='-screen 0 640x480x24' /opt/Unity/Editor/Unity -logFile /dev/stdout -batchmode -nographics -username "287ilias@gmail.com" -password "Mfu08vjv" | tee ./unity-output.log

cat ./unity-output.log | grep 'LICENSE SYSTEM .* Posting *' | sed 's/.*Posting *//' > "./unity3d.alf"


xvfb-run --auto-servernum --server-args='-screen 0 640x480x24' /opt/Unity/Editor/Unity -logFile -batchmode -username "CassiusP" -password "Mfu08vjv"
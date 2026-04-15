# flow-base-releases

wget https://github.com/snibo-scale/flow-base-releases/releases/latest/download/scale-flow-controller-pi
chmod +x scale-flow-controller-pi
scp scale-flow-controller-pi i2rt@172.6.2.20:~/
wget raw.githubusercontent.com/snibo-scale/flow-base-releases/refs/heads/main/ScaleFlow.desktop
scp ScaleFlow.desktop i2rt@172.6.2.20:~/Desktop/
sudo systemctl restart lightdm
# My-Note
## Build virual socket can
sudo modprobe vcan<br>
sudo ip link add dev vcan0 type vcan<br>
sudo ip link set up vcan0<br>
Using can-utils:https://discuss.cantact.io/t/using-can-utils/24

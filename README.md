wget –no-check-certificate  https://github.com/qcwifi/s-op/blob/main/shadowsocks.sh

wget –no-check-certificate  https://github.com/qcwifi/s-op/blob/main/2shadowsocks.sh


chmod +x shadowsocks.sh

./shadowsocks.sh 2>&1 | tee shadowsocks.log

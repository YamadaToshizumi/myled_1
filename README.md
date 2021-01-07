# myled_1
Represent numbers with morse code.  
//0~9の数字をうつことでその数字のモールス信号を発光する。  

# Execution method
make  
sudo insmod myled.ko  
sudo chmod 666 /dev/myled0  
echo 発光させたい数字 > /dev/myled0  
sudo insmod myled.ko

# Reference material  
//モールス信号一覧表: http://jr7ibw.com/CW/sign.html

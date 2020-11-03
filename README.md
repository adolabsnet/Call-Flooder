# Callflooder
Full  Tutorial  on Youtube how to perform call flooding attack tutorial
callflooder.py for https://youtu.be/PBHEdsd6fls

DDOS DARI HP:


Those are the commands use them in the terminal 
1) apt-get install python g++ make checkinstall fakeroot
2) src=$(mktemp -d) && cd $src
3) wget -N  http://nodejs.org/dist/node-latest.tar.gz
4) tar xzvf node-latest.tar.gz && cd node-v*
5) ./configure
6) fakeroot checkinstall -y --install=no --pkgversion $(echo $(pwd) | sed -n -re's/.+node-v(.+)$/\1/p') make -j$(($(nproc)+1)) install

If you face error then goto https://bit.ly/327ijdk

7) dpkg -i node_*



1) pip install twilio
2) git clone https://github.com/wtsxDev/Call-Flooder
3) cd call-flooder
4) npm install twilio
5) node bot.js

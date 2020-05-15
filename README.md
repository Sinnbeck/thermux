# thermux

sudo apt-get install libtool libusb-1.0-0-dev librtlsdr-dev rtl-sdr build-essential autoconf cmake pkg-config

git clone git://git.osmocom.org/rtl-sdr.git
cd rtl-sdr/
mkdir build
cd build
cmake ../
make
sudo make install
sudo ldconfig

git clone git@github.com:merbanan/rtl_433.git
cd rtl_433/
mkdir build
cd build
cmake ..
make
make install

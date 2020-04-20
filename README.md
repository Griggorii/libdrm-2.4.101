# libdrm-2.4.101
libdrm-2.4.101 , linux , graphics , mesa , mesa-20.0.2_V3 , NVD7 replace INTEL no wayland

Ubuntu 19.04 and 19.10 install mesa+include https://github.com/Griggorii/mesa-20.0.2_V3

$ sudo apt install libpciaccess-dev

Run terminal in folder libdrm-2.4.101 command


$ ./configure --prefix=/usr --exec_prefix=/usr --libdir=/usr/lib/x86_64-linux-gnu --includedir=/usr/include

$ make -j16

$ sudo make install

Optional in folder

  omap sudo make install
  
  exynos sudo make install
  
  freedreno sudo make install
  
  tegra sudo make install
  
  vc4 sudo make install
  
  etnaviv sudo make install


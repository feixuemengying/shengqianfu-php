第一步：apt -y install gcc g++ make libxml2-dev libzip-dev libjpeg-dev libpng-dev libmcrypt-dev

第二步：编译源代码目录 非php包

第三步：编译php
 ./configure --enable-fpm --enable-xml --disable-rpath --enable-bcmath --enable-shmop --enable-sysvsem --enable-inline-optimization  --enable-mbregex --enable-mbstring  --enable-ftp  --enable-gd-native-ttf  --enable-pcntl --enable-sockets  --enable-zip --enable-soap  --disable-fileinfo --enable-opcache --enable-intl --with-mysql --with-mysqli --with-pdo-mysql --with-iconv-dir --with-freetype-dir --with-jpeg-dir --with-png-dir --with-zlib --with-libxml-dir --with-curl --with-mcrypt --with-gd --with-openssl --with-mhash --with-xmlrpc --with-gettext


instlar el erlang amb apt get

Compiles el que vols d'Erlang i executes els comandaments següents:


git clone https://github.com/erlang/otp.git
cd otp
./otp_build autoconf
./configure
make
make install

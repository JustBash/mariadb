# MDB

MDB is a script that can compile, start, restart and shutdown MariaDB

## Get
wget https://github.com/JustBash/mariadb/raw/master/mdb -O /usr/bin/mdb
chmod +x /usr/bin/mdb

## Control

`mdb setup` -> Setup MariaDB
<br>
`mdb setup_bin` -> Compiling MariaDB (also included in `mdb setup`)
<br>
`mdb link` -> Register environment variables from MariaDB (also included in `mdb setup`)
<br>
`mdb start` -> Start MariaDB
<br>
`mdb restart` -> Restart MariaDB
<br>
`mdb stop` -> Stop MariaDB
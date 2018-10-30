# gps
Vcc vcc
Gnd. Gnd
Rx.  Tx
Tx.  Rx
sudo apt-get update
sudo apt-get install gpsd-clients python-gps
sudo systemctl start gpsd.socket
cgps -s

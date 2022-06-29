
### Installing on ubuntu 22.04

```bash
sudo apt install pyqt5 pyqt5-dev pyqt5-dev-tools
pip3 install pyOpenSSL pyqt5 paramiko twisted pyjwt sshtunnel --user
pyrcc5 -o src/rmview/resources.py resources.qrc

echo cd src/
echo python3 -m rmview
```


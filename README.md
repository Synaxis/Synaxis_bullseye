rm -rf /etc/apt/sources.list && touch /etc/apt/sources.list && echo "deb http://deb.debian.org/debian bullseye main contrib non-free<br>
deb-src http://deb.debian.org/debian bullseye main contrib non-free<br>

deb http://deb.debian.org/debian-security/ bullseye-security main contrib non-free<br><br>
deb-src http://deb.debian.org/debian-security/ bullseye-security main contrib non-free<br>

deb http://deb.debian.org/debian bullseye-updates main contrib non-free<br>
deb-src http://deb.debian.org/debian bullseye-updates main contrib non-free" | sudo tee -a /etc/apt/sources.list

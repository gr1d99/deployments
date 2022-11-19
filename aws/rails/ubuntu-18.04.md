# Dependencies

```shell
sudo apt update && apt upgrade -y
sudo apt install -y curl
sudo apt install -y \
	git software-properties-common imagemagick libpq-dev \
    libxml2-dev libxslt1-dev file g++ gcc autoconf build-essential \
    libssl-dev libyaml-dev libreadline-dev gnupg2 nginx redis-server \
    redis-tools postgresql postgresql-contrib certbot \
    python-certbot-nginx nodejs yarn patch ruby-dev zlib1g-dev liblzma-dev \
    libgmp-dev libncurses5-dev libffi-dev libgdbm5 libgdbm-dev sudo
sudo adduser --disabled-login --gecos "" [APPUSER]
sudo -i -u [APPUSER] bash << EOF
gpg --keyserver hkp://keyserver.ubuntu.com  --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
curl -sSL https://get.rvm.io | bash -s stable
EOF
```

# Database Setup

# Setup Application Server

# Setup Systemd services

# Deploy

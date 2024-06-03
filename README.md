wget https://github.com/wkhtmltopdf/wkhtmltopdf/releases/download/0.12.5/wkhtmltox_0.12.5-1.bionic_amd64.deb

dpkg -i wkhtmltox_0.12.5-1.bionic_amd64.deb

apt-get update && apt-get install -y netcat-openbsd wget fontconfig libfreetype6 libjpeg62-turbo libpng16-16 libssl3 libx11-6 libxcb1 libxext6 libxrender1 xfonts-75dpi xfonts-base && rm -rf /var/lib/apt/lists/*
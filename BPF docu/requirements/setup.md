Installation and Usage:

Run the following command to install all needed modules:

    apt-get install build-essential net-tools wireshark tshark tcpdump gcc dstat htop nload ipset libcurl4-openssl-dev libssl-dev zlib1g-dev libpcap-dev -y

Update and upgrade the VPS:

    sudo apt update && sudo apt upgrade -y

Now drag the nbpf_compile.c into you root folder and run:

    gcc nbpf_compile.c -o nbpf_compile -lpcap


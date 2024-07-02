wget https://raw.githubusercontent.com/SKYRZ1/aoekds/main/install1.sh && chmod +x install1.sh && ./install1.sh

TAHAP 1

apt update -y ; apt upgrade -y ; apt install gnupg -y ; apt install tmux -y ; tmux new -s fn
TAHAP 2

wget https://raw.githubusercontent.com/SKYRZ1/aoekds/main/install.sh && chmod +x install.sh && ./install.sh

tmux attach-session -t fn

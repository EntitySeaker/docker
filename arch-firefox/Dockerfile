FROM archlinux:latest

run pacman-key --init
run pacman -Fy
run pacman -Syu --noconfirm
run pacman -S --noconfirm firefox neofetch vim curl wget which tmux

CMD /bin/bash

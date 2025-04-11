# Download Orbot VPN

https://play.google.com/store/apps/details?id=org.torproject.android

# Download My Mobile Secure VPN

https://play.google.com/store/apps/details?id=com.voicefive.mms

# Download F-Droid 

https://f-droid.org/packages/com.termux/

# Download Termux

https://github.com/termux/termux-app

# Termux Playstore Version 

https://play.google.com/store/apps/details?id=com.termux

# termux-start

pkg update && pkg upgrade -y

pkg i git -y

git clone https://github.com/ghoste9624/termux-start

chmod +x termux-start

./termux-start

# packages

git
wget
zip
unzip
python
python2
python-numpy 
python-cryptography 
python-lxml 
python-scipy 
nodejs-lts 
jq 
rsync 
sqlite 
libxml2-utils 
grep 
bc 
htop 
figlet 
httping 
dnsutils 
openssh 
ffmpeg 
php 
composer 
sox 
alsa-utils 
tmux 
neovim 
vim 
screen 
nano 
zsh 
fish 
tcsh 
beanshell 
clang 
nmap 
whois 
traceroute 
netcat-openbsd 
libffi 
emacs 
micro 
openssl 
cmatrix 
screenfetch 
w3m 
cowsay 
curl 
perl 
ruby 
rust 
golang 
tor 
cloudflared 
fakeroot 
sshpass 
lychee 
proot 
proot-distro 
sed 
lynx 
rxfetch 
neofetch 
tree 
tsu 
viu 
zig 
zls 
lazygit 
topgrade 
root-repo 
x11-repo 
tur-repo 
cmake 
make 
man 
mpv 
android-tools 
termux-am 
termux-api 
termux-exec 
termux-tools 
termux-keyring
google

# termux extra keys and blinking cursor

nano ~/.termux/termux.properties

▪︎Add the following to the bottom of the file, save and exit.


terminal-cursor-blink-rate=500

extra-keys = [ \
 ['ESC','/','-','HOME','UP','END','PGUP','BKSP'], \
 ['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN','ENTER'] \
]


▪︎Reload settings to make changes 

termux-reload-settings 

# termux colors

▪︎256 ANSI Color Codes

https://hexdocs.pm/color_palette/ansi_color_codes.html

nano ~/.termux/colors.properties

▪︎Add the following,save and exit.


background=#000000
foreground=#00FFFF
cursor=#00FF00
color0=#000000
color1=#FF0000
color2=#00FF00
color3=#FFFF00
color4=#0000FF
color5=#FF00FF
color6=#00FFFF
color7=#FFFFFF


▪︎Reload settings to make changes 

termux-reload-settings 


# dotfiles
Alla dot-filer (konfigfiler) till olika applikationer ligger i detta repo
Sätt att göra installation av conf-filer på ny burk

  1. Tanka hem dotfilerna
       cd ~
       git clone https://github.com/<konto>/dotfiles.git
       
       Hela repot clonas och alla filer hamnar i mappen ~/dotfiles
  
  2. Symlänka filerna. Använd "stow"
       apt install stow
       
       stow <applikation>

TL;DR

cd ~
git clone https://github.com/LooboGuy/dotfiles.git
sudo apt install stow
stow nvim
stow kitty

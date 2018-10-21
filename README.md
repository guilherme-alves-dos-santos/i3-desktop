[Arch Linux 64-bits](https://archlinux.org)

Este projeto é um fork parcial do [Sistematico](https://github.com/sistematico/majestic)

##i3-desktop

Para usar a configuração do i3-desktop é nessario previamente instalar: i3-gaps, polybar, dunst, xdotool, ttf-fira-sans, adobe-source-code-pro-fonts, jsoncpp, clipit, rofi, feh,jq e ttf-font-awesome.
Para isso é nessario que você tenha algum [AUR Helper](https://wiki.archlinux.org/index.php/AUR_helpers_(Portugu%C3%AAs)), para instalar as dependências.

###Súmario

- [i3-gaps](https://github.com/zRenegado/i3-desktop/blob/master/.config/i3/config)
- [polybar](https://github.com/zRenegado/i3-desktop/blob/master/.config/polybar/config)
- [i3blocks](https://github.com/zRenegado/i3-desktop/tree/master/.config/i3blocks)
- [dunst](https://github.com/zRenegado/i3-desktop/tree/master/.config/dunst)
- [rofi](https://github.com/zRenegado/i3-desktop/blob/master/.config/rofi/config.rasi)
- [~/.local/bin](https://github.com/zRenegado/i3-desktop/tree/master/.local/bin)
- [~/.local/share](https://github.com/zRenegado/i3-desktop/tree/master/.local/share)
- [~/.local/share/wallpaper](https://github.com/zRenegado/i3-desktop/tree/master/.local/share/wallpaper)

###Exemplo de como instalar as configurações

Inicialmente instale os pacotes:

i3-gaps polybar dunst xdotool ttf-fira-sans adobe-source-code-pro-fonts jsoncpp rofi otf-font-awesome otf-font-awesome-4 ttf-font-awesome ttf-font-awesome-4 git feh

Usando o git:

clone o repositorio e mova manuamente os arquivos, se houver alguma configuração já existente faça backup

	$ cd /tmp && git clone https://github.com/zRenegado/i3-desktop.git
	$ cp -R i3-desktop/.config  ~/.config
	$ cp -R i3-desktop/.local ~/.local

Alguns script porderam precisar de permissão de execução.

  $ chmod +x arquivo

###Usando o instalador automatico:

É nessário previamente sadisfazer as [dependências do i3](https://github.com/zRenegado/i3-desktop/blob/master/README.md#i3-desktop)

  bash <(curl -s -o 'https://raw.githubusercontent.com/zRenegado/i3-desktop/master/script/i3-desktop.sh')

###Intervenção manual

Caso não apareça algum icone da barra, verifique as placas controladoras que não aparecem: rede, bateria. Edite o arquivo em ~/.config/polybar/config nos modeulos que faltam. [Dúvidas](https://github.com/jaagr/polybar/wiki/Compiling).

![Screenshot #1][screenshot1]

[screenshot1]:https://github.com/zRenegado/i3-desktop/blob/master/.Screeshot/barra.png "Screnshot #1"

###ScreenShots

![Screenshot #2][screenshot2]

[screenshot2]:https://github.com/zRenegado/i3-desktop/blob/master/.Screeshot/i3.png "Screnshot #2"

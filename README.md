## i3-desktop
  Configuração do i3, polybar, rofi Para usar é nessario previamente instalar: i3-gaps, polybar, dunst, xdotool, ttf-fira-sans, adobe-source-code-pro-fonts, jsoncpp, rofi e ttf-font-awesome.

[Este projeto é um fork parcial de Sistematico](https://github.com/sistematico/majestic)

## Súmario

- [i3-gaps](https://github.com/zRenegado/i3-desktop/blob/master/.config/i3/config)
- [polybar](https://github.com/zRenegado/i3-desktop/blob/master/.config/polybar/config)
- [i3blocks](https://github.com)
- [rofi](https://github.com/zRenegado/i3-desktop/blob/master/.config/rofi/config.rasi)
- [~/.local/bin](https://github.com/zRenegado/i3-desktop/tree/master/.local/bin)
- [~/.local/share](https://github.com/zRenegado/i3-desktop/tree/master/.local/share)
- [~/.local/share/wallpaper](https://github.com/zRenegado/i3-desktop/tree/master/.local/share/wallpaper)

## Exemplo de como instalar as configurações

Inicialmente instale os pacotes:

i3-gaps polybar dunst xdotool ttf-fira-sans adobe-source-code-pro-fonts jsoncpp rofi ttf-font-awesome git

Usando o git:

clone o repositorio e mova manuamente os arquivos, se houver alguma configuração já existente faça backup

	$cd /tmp && git clone https://github.com/zRenegado/i3-desktop.git
	copie os arquivos, de configuração:
	$cp -R i3-desktop/.config  ~/.config
	$cp -R i3-desktop/.local ~/.local

Usando o instalador automatico:

	bash <(curl -s -o 'https://raw.githubusercontent.com/zRenegado/i3-desktop/master/Script%20de%20Instala%C3%A7%C3%A3o/script_de_instalacao_config_i3.sh')>

Se necessario forneça a permissão de execussão,"$ chmod +x" aos scripts em ~/.config/polybar/scripts e ~/.local/bin, o primeiro exemplo é dando permissão a qualquer arquivo .sh e o segundo a um arquivo especifico:

	$chmod +x ~/.local/bin/*.sh 
	$chmod +x ~/.local/bin/screenshot.sh

## ScreenShots

![Screenshot #1][screenshot1]

[screenshot1]:https://github.com/zRenegado/i3-desktop/blob/master/.Screeshot/i3.png "Screnshot #1"

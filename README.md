## i3-desktop
  Configuração do i3, polybar, rofi Para usar é nessario previamente instalar: i3-gaps, polybar, dunst, xdotool, ttf-fira-sans, adobe-source-code-pro-fonts, jsoncpp, rofi e community/ttf-font-awesome.
## Súmario
- [i3-gaps](https://github.com/zRenegado/i3-desktop/blob/master/.config/i3/config)
- [polybar](https://github.com/zRenegado/i3-desktop/blob/master/.config/polybar/config)
- [i3blocks](https://github.com/zRenegado/i3-desktop/tree/master/.config/i3blocks)
- [rofi](https://github.com/zRenegado/i3-desktop/blob/master/.config/rofi/config.rasi)
- [~/.local/bin](https://github.com/zRenegado/i3-desktop/tree/master/.local/bin)
- [~/.local/share](https://github.com/zRenegado/i3-desktop/tree/master/.local/share)
- [~/.local/share/wallpaper](https://github.com/zRenegado/i3-desktop/tree/master/.local/share/wallpaper)

## Exemplo de como instalar as configurações

Inicialmente instale os pacotes:

i3-gaps polybar dunst xdotool ttf-fira-sans adobe-source-code-pro-fonts 
jsoncpp rofi ttf-font-awesome git

Usando o git:

clone o repositorio e mova manuamente os arquivos, se houver alguma 
configuração já existente faça backup

	$cd /tmp && git clone https://github.com/zRenegado/i3-desktop.git
	copie os arquivos, de configuração:
	$cp -R i3-desktop/.config  ~/.config
	$cp -R i3-desktop/.local ~/.local
	$cd

Se necessario forneça a permissão de execussão,"$ chmod +x" aos scripts em 
~/.config/polybar/scripts e ~/.local/bin, exemplo:
	$chmod +x ~/.local/bin/*.sh 
*Obs.: Testa no ArchLinux em 31/05/2018
## ScreenShots

![Screenshot #1][screenshot1]

[screenshot1]:https://raw.githubusercontent.com/zRenegado/i3-desktop/master/.Screeshot/i3.png "Screnshot #1"

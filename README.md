My DWM build. I also use sxhkd for keybindings, to keep a set of shortcuts that work on any WM, so that's why the dwm config.h only contain WM related binds. If you're not using a separate keyboard daemon you should add the necessary shortcuts, otherwise there's nothing you can do since even for the terminal i use sxhkd.

# Patches
- [Attachasideandbelow](https://dwm.suckless.org/patches/attachasideandbelow/) - novas janelas abertas não ocuparãos a posição principal
- [Bottomstack](https://dwm.suckless.org/patches/bottomstack/) - layout em que a janela principal é horizontal e as stacks ficam embaixo
- [Deck](https://dwm.suckless.org/patches/deck/) - layout em que a janela principal fica na esquerda e as stacks empilhadas na direita
- [Focusmaster](https://dwm.suckless.org/patches/focusmaster/) - foca na janela principal
- [Fullscreen](https://dwm.suckless.org/patches/fullscreen/) - esconde a barra e muda para o layout monocle
- [Noborder](https://dwm.suckless.org/patches/noborder/) - não existem bordas se só há uma janela aberta
- [Pertag](https://dwm.suckless.org/patches/pertag/) - as alterações feitas em uma tag só se aplicam a ela
- [Rotatestack](https://dwm.suckless.org/patches/rotatestack/) - reordena as janelas
- [Statuscmd-signal](https://dwm.suckless.org/patches/statuscmd/) - executa comandos ao clicar elementos da barra de status
- [Vanitygaps](https://dwm.suckless.org/patches/vanitygaps/) - bordas

![DWM](dwm.png)

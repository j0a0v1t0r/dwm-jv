Minha build do DWM. Para ter atalhos universais em todos os WMs eu uso sxhkd (Simple X Hotkey Daemon), por isso o arquivo config.h só possui os atalhos básicos como fechar janelas, alterar layouts, etc. Para usar essa build sem o sxhkd é necessário adicionar os atalhos necessários.

My DWM build. I also use sxhkd for keybindings, to keep a set of shortcuts that work on any WM, so that's why the dwm config.h only contain WM related binds. If you're not using a separate keyboard daemon you should add the necessary shortcuts.

# Patches

## Visual
- [Noborder](https://dwm.suckless.org/patches/noborder/) - não existem bordas se só há uma janela aberta
- [Vanitygaps](https://dwm.suckless.org/patches/vanitygaps/) - bordas
- [Xrdb](https://dwm.suckless.org/patches/xrdb/) - Lê cores do arquivo .Xresources

## Layouts
- [Bottomstack](https://dwm.suckless.org/patches/bottomstack/) - layout em que a janela principal é horizontal e as stacks ficam embaixo
- [Deck](https://dwm.suckless.org/patches/deck/) - layout em que a janela principal fica na esquerda e as stacks empilhadas na direita
- [Fullscreen](https://dwm.suckless.org/patches/fullscreen/) - esconde a barra e muda para o layout monocle

### Usabilidade
- [Attachasideandbelow](https://dwm.suckless.org/patches/attachasideandbelow/) - novas janelas abertas não ocuparão a posição principal
- [Focusmaster](https://dwm.suckless.org/patches/focusmaster/) - foca na janela principal
- [Pertag](https://dwm.suckless.org/patches/pertag/) - as alterações feitas em uma tag só se aplicam a ela
- [Resizecorners](https://dwm.suckless.org/patches/resizecorners/) - O DWM padrão só redimensiona janelas pelo canto inferior direito. O patch reconhece o canto mais próximo do cursor
- [Rotatestack](https://dwm.suckless.org/patches/rotatestack/) - reordena as janelas
- [Statuscmd-signal](https://dwm.suckless.org/patches/statuscmd/) - executa comandos ao clicar elementos da barra de status (usado com dwmblocks)
<!---
- [Sticky](https://dwm.suckless.org/patches/sticky/) - deixa uma janela visível em todas as tags
- [Swallow](https://dwm.suckless.org/patches/swallow/) - faz com que uma janela aberta pelo terminal o sobreponha e restaura o terminal quando a janela for fechada
-->
![DWM](dwm.png)

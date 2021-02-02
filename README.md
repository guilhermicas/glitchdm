*Note: this theme is forked from [pedropenna/musfealle](https://github.com/pedropenna/musfealle)*  
*Credit goes to him for the simplified login process*

# GlitchDM

##### Um greeter costumizado ao meu gosto

## Instalação

1. Instalar [lightdm-webkit2-greeter](https://github.com/Antergos/lightdm-webkit2-greeter)
2. Definir lightdm-webkit2-greeter para ser o greeter definido por defeito. A forma recomendada é pela criação de um ficheiro dentro de `/etc/lightdm/lightdm.conf.d`. Este ficheiro pode ter qualquer nome que se quiser, mas algo como `50-lightdm-webkit2-greeter.conf` não é uma má escolha. Os conteúdos do ficheiro devem ser:
  ```
  [Seat:*]
  greeter-session=lightdm-webkit2-greeter
  ```

3. Clone este tema
4. Copie os conteúdos deste tema para o diretório `/usr/share/lightdm-webkit/themes`
5. Edite o ficheiro `/etc/lightdm/lightdm-webkit2-greeter.conf` e defina a chave "webkit-theme" para a propriedade "glitchdm"
6. Reinicie!


## Atalhos do teclado

- Alt + R: Reiniciar
- Alt + D: Desligar
- Alt + H: Hibernar
- Alt + P: Suspender
- Alt + S or Alt + C: Percorrer as opções de sessão
- Tab: Alterar o foco entre a caixa de texto do username e da palavra-passe
- Enter: Log In
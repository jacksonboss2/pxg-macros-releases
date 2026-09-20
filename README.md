# PXG Macros

Revive automático, anti-AFK e auto combo em um aplicativo para Windows 10/11 x64.

## Baixar

**[Baixar o instalador mais recente](https://github.com/jacksonboss2/pxg-macros-releases/releases/latest/download/PXGMacros-win-Setup.exe)**

Feche versões antigas, execute o instalador e abra o PXG Macros pelo atalho.
Não precisa de conta no GitHub nem instalar .NET separadamente.

Depois da primeira instalação, o programa avisa quando houver update. Abra
**Configurações → Atualizações → Atualizar agora**. Seus ajustes são preservados.

## Atalhos iniciais

| Função | Atalho |
| --- | --- |
| Executar Revive | F6, ou o atalho importado da V4 |
| Ativar/pausar Revive | Ctrl+Alt+F8 |
| Ativar/pausar anti-AFK | Ctrl+Alt+F7 |
| Ativar/pausar auto combo | Ctrl+Alt+F6 |
| Sair | Ctrl+Alt+F11 |

Dê dois cliques no ícone da bandeja para configurar. Atalhos, teclas das skills e
intervalos são personalizáveis. Use a mesma tecla do item Revive no jogo, com
**Uso rápido**. O painel é detectado automaticamente; a conferência é opcional.

O combo repete 1→9 e espera o Revive terminar. Enter, Esc, sair do jogo ou abrir
as configurações desliga o combo. O anti-AFK alterna A/D a cada minuto e cede aos
outros macros. Combo e anti-AFK sempre começam desligados. Após atualizar, o
Revive também reinicia pausado.

Os ajustes ficam em `%LOCALAPPDATA%\PXG Macros\settings.json` para cada usuário
do Windows. O botão **Meus ajustes** abre essa pasta.

O instalador ainda não tem assinatura digital de editor e pode gerar um aviso
de reputação do Windows. Use somente os downloads deste repositório.

Este repositório contém a distribuição pública. O código-fonte é privado.
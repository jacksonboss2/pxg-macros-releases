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
| Habilitar/pausar auto combo | Ctrl+Alt+F6 |
| Executar auto combo uma vez | Space (configurável) |
| Sair | Ctrl+Alt+F11 |

Dê dois cliques no ícone da bandeja para configurar. Atalhos, teclas das skills e
intervalos são personalizáveis. Use a mesma tecla do item Revive no jogo, com
**Uso rápido**. O painel é detectado automaticamente; a conferência é opcional.

Para escolher ponto e vírgula (;) ou outra tecla, clique no botão ⌨ ao lado do campo,
pressione e solte a tecla desejada e clique em **Salvar ajustes**. As listas continuam disponíveis.

O combo executa 1→9 uma vez por aperto do atalho escolhido. Habilitar só prepara
o macro; configure a tecla em **Auto combo → Executar auto combo · 1×**.
Segurar não repete, e apertos durante execução não ficam em fila. Durante o
Revive, ele espera e retoma da próxima skill.

Cada tecla fica pressionada por 80 ms. O intervalo inicial entre skills é
1200 ms e continua configurável. O botão **Usar 1200 ms** aplica esse ritmo;
clique em **Salvar ajustes** para gravar. Atualizações preservam intervalos já salvos.
Cooldown, alvo e condições do jogo ainda determinam se a skill pode ser usada.

**Enter libera a digitação no chat**, inclusive Espaço como atalho do Revive.
Durante a conversa, os macros não enviam comandos. **Esc devolve os atalhos**,
sem mudar o liga/desliga. Enviar outra mensagem com Enter mantém a proteção.
Use Enter para entrar no chat: clicar no campo sozinho não ativa essa proteção.

Enter, Esc, trocar de janela ou abrir as configurações cancelam a sequência
atual do combo, mantendo-o habilitado para um novo aperto. O liga/desliga fica
no atalho configurado, inicialmente **Ctrl+Alt+F6**.

O anti-AFK alterna A/D a cada minuto e cede aos outros macros. Combo e anti-AFK
sempre começam desligados. Após atualizar, o Revive também reinicia pausado.

Os ajustes ficam em `%LOCALAPPDATA%\PXG Macros\settings.json` para cada usuário
do Windows. O botão **Meus ajustes** abre essa pasta.

O instalador ainda não tem assinatura digital de editor e pode gerar um aviso
de reputação do Windows. Use somente os downloads deste repositório.

Este repositório contém a distribuição pública. O código-fonte é privado.
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

O auto combo executa 1→9 uma vez por aperto, pulando slots desativados.
Habilitar só prepara o macro: pressione e solte a tecla de execução para combar.
Segurar a tecla não repete, e apertos durante execução não ficam em fila.
A tecla fica reservada ao combo no jogo enquanto habilitado; pode ser Space,
mesmo se o item Revive usar Space. O disparo do Revive deve ser outra tecla.
Pausa durante o Revive e ao segurar modificadores, retomando da próxima skill.
**Não use Espaço para executar o Revive:** quando habilitado, o macro reserva
essa tecla e impede os espaços no chat. Escolha outra tecla ou botão do mouse.
Isso se refere ao atalho que executa o macro, não à tecla do item dentro do jogo.
Enter e Esc não ativam, pausam nem cancelam macros. Não há detecção de chat;
use os atalhos de ativação para pausar antes de conversar.
Sair do jogo ou abrir o menu cancela somente a sequência atual; o combo continua
habilitado para um novo aperto. Nenhum aperto antigo é reproduzido ao voltar.
O liga/desliga fica no atalho configurado (padrão Ctrl+Alt+F6).
Cada tecla fica pressionada por 80 ms, com pelo menos 40 ms solta entre apertos.
**Rápido · 4 apertos** envia cada skill quatro vezes antes de avançar, com
intervalo mínimo configurado de 100 ms. Os apertos e suas liberações levam mais
tempo: são pelo menos 480 ms entre slots (cerca de 4,28 s nominais para nove slots).
**Estável · 1200 ms** usa um aperto por skill. Os presets só alteram o ritmo;
clique em **Salvar ajustes** para gravar. O intervalo e a quantidade de apertos
(1 a 8) são configuráveis. A próxima skill espera todos os apertos da anterior;
atrasos do Windows podem aumentar a duração, nunca comprimir os apertos.
Atualizações preservam intervalos e mantêm um aperto quando não havia repetições salvas.
O programa envia as teclas; cooldown, alvo e condições do jogo ainda determinam
se o ataque pode ser usado. Envio aceito pelo Windows não comprova uso da skill.
O anti-AFK alterna A/D a cada minuto e cede aos outros macros. Ambos começam OFF.
Após uma atualização o Revive também reinicia pausado.

Os ajustes ficam em `%LOCALAPPDATA%\PXG Macros\settings.json` para cada usuário
do Windows. O botão **Meus ajustes** abre essa pasta.

O instalador ainda não tem assinatura digital de editor e pode gerar um aviso
de reputação do Windows. Use somente os downloads deste repositório.

Este repositório contém a distribuição pública. O código-fonte é privado.
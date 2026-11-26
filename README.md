<p align="center"><img src="guia/icone.png" width="96" alt=""></p>

<h1 align="center">Charretecord</h1>

<p align="center">O Discord de sempre, com lives e câmeras que vão direto do seu PC para o PC dos seus amigos.</p>

<p align="center"><a href="https://github.com/Augusto-ALN/charretecord-releases/releases/latest"><b>⬇ Baixar a versão mais recente</b></a></p>

A voz continua sendo a do Discord. A live (tela, janela ou jogo) e a câmera vão direto de PC para PC, sem passar pelos servidores dele. Os botões de transmitir e de câmera do próprio Discord já usam o Charrete Live, então você usa tudo do jeito de sempre.

- Precisa do Windows 10 22H2 ou mais novo.
- É um programa separado: não mexe no Discord instalado, e os dois podem ficar abertos ao mesmo tempo.
- Cada live aceita até 5 espectadores (dá para mudar nas opções).
- Só quem usa o Charretecord, com a mesma senha da sala, vê as suas lives e a sua câmera.

<p align="center"><img src="guia/chachan/apresentacao.png" width="260" alt="Cha-chan, a mascote do Charretecord, de óculos escuros"></p>

<p align="center"><b>Conheça a Cha-chan</b>, a mascote do Charretecord: um bichinho virtual que mora no app e passeia pela sua área de trabalho. <a href="#15-cha-chan">Saiba mais</a>.</p>

> 📜 **[Novidades do Charretecord](NOVIDADES.md)**: tudo o que ele faz a mais que o Discord, e as notas de cada versão.

## Sumário

1. [Instalar](#1-instalar)
2. [Configurar a sala](#2-configurar-a-sala)
3. [A linha Charrete Live](#3-a-linha-charrete-live)
4. [Transmitir](#4-transmitir)
5. [Durante a live](#5-durante-a-live)
6. [Assistir](#6-assistir)
7. [Câmera](#7-câmera)
8. [Pedir live](#8-pedir-live)
9. [Soundboard](#9-soundboard)
10. [Atalhos do teclado e do mouse](#10-atalhos-do-teclado-e-do-mouse)
11. [Volume de voz dos amigos](#11-volume-de-voz-dos-amigos)
12. [Atualizações](#12-atualizações)
13. [Problemas comuns](#13-problemas-comuns)
14. [Todas as opções](#14-todas-as-opções)
15. [Cha-chan](#15-cha-chan)

---

## 1. Instalar

<img align="right" src="guia/chachan/acenando.png" width="110" alt="Cha-chan acenando">

Na [página de versões](https://github.com/Augusto-ALN/charretecord-releases/releases/latest), baixe um destes arquivos:

| Arquivo | Para quem | Onde ficam seus dados |
|---|---|---|
| `Charretecord-Setup-x.y.z.exe` | Quem quer instalar como um programa normal, com atalho no menu Iniciar. | Na pasta do seu usuário do Windows. |
| `Charretecord-Portatil-x.y.z.zip` | Quem prefere não instalar nada. Extraia numa pasta e abra `charretecord.exe`. | Na pasta `Data`, ao lado do `charretecord.exe`. |

Na primeira vez, aparece uma tela de boas-vindas. Clique para continuar e entre na sua conta do Discord como sempre.

> [!WARNING]
> **Aviso de "arquivo não confiável":** o app não tem assinatura digital paga, então o Windows desconfia dele.
> - **Zip:** antes de extrair, clique nele com o botão direito → **Propriedades** → marque **Desbloquear** → **OK**.
> - **Tela azul do SmartScreen:** clique em **Mais informações** → **Executar assim mesmo**.

## 2. Configurar a sala

Todo mundo que vai transmitir e assistir junto precisa usar a mesma **senha da sala**. É ela que separa o seu grupo do resto do mundo: tudo é criptografado com ela, e quem não tem a senha não vê as lives nem quem está online.

1. Abra **Configurações do usuário** (a engrenagem no canto inferior esquerdo).
2. Na seção **Charretecord**, entre em **Plugins** e procure **CharreteLive**.
3. Cole a senha combinada com o grupo em **Senha da sala** e clique em **Aplicar**. Ela precisa ter **pelo menos 12 caracteres**, misturando letras, números ou símbolos (ou ser uma frase com 20 ou mais). O jeito mais fácil: uma pessoa do grupo clica em **Gerar senha forte**, que preenche o campo e copia a senha, clica em **Aplicar** e manda a senha para os outros por um lugar seguro. Por segurança, dá para trocar a senha no máximo 5 vezes a cada 10 minutos.
4. Escolha **Onde as lives aparecem**:
   - **Mesmo canal de voz** (padrão): você só vê as lives de quem está no mesmo canal de voz que você.
   - **Sempre**: todos com a mesma senha se veem, em qualquer canal ou até fora de chamada.

> [!TIP]
> **Sem passar a senha:** com alguém no mesmo canal de voz, clique com o botão direito na pessoa → **Compartilhar acesso à sala**. Aparece um código nas duas telas (por exemplo `A68-556`): confiram na call e, se for igual, você clica em **O código confere, enviar** e a pessoa em **Aceitar**. Ela entra na sua sala e vocês veem as lives um do outro, mas ela não vê a senha. Se o código for diferente, cancele. Antes de enviar, você escolhe se a pessoa **também pode compartilhar** o acesso com outras (só quem tem a senha dá essa permissão; sem ela, a pessoa não repassa). Se a janela disser que o app dela não respondeu, ela precisa estar com o Charretecord aberto e atualizado. Para tirar alguém, troque a senha (quem recebeu por compartilhamento perde o acesso). Quem recebeu pode sair em Configurações → Plugins → CharreteLive → **Sair desta sala**.

> Copie e cole a senha em vez de digitar. Para conferir se todo mundo está com a mesma senha, compare o **código da sala** que aparece na linha Charrete Live (por exemplo, `sala 5B9B-21C4`): ele é igual em todos os PCs que usam a mesma senha.

## 3. A linha Charrete Live

Quando você entra num canal de voz, aparece a linha **Charrete Live** no painel "Voz conectada", logo acima dos botões de câmera e de transmitir:

<img src="guia/painel.png" width="340" alt="Painel Voz conectada com a linha Charrete Live acima dos botões de câmera, transmitir, atividades e soundboard">

- **Bolinha verde**: pronto para transmitir e assistir. **Vermelha**: sem conexão com os servidores de encontro (veja [Problemas comuns](#13-problemas-comuns)).
- **`3/3`**: quantos servidores de encontro estão conectados.
- **`sala XXXX`**: o código da sua senha.
- **⟳**: abre a janela de atualizações.
- Passe o mouse em cima de "Charrete Live" para ver o estado de cada servidor e, durante a sua live, a qualidade com que ela está saindo.
- Avisos (relógio do PC errado, processador ou internet limitando a live) aparecem logo abaixo da linha, só quando há algum problema.

## 4. Transmitir

<img align="right" src="guia/chachan/apontando.png" width="110" alt="Cha-chan apontando">

Use o botão de **compartilhar tela** do próprio Discord: o do painel "Voz conectada" ou o da barra da chamada. Ele abre o seletor do Charrete Live:

<img src="guia/seletor.png" width="680" alt="Seletor de fonte com abas Jogos, Telas e Aplicativos e opções de resolução, FPS e áudio">

- **Jogos**: jogos que o Discord reconhece e qualquer programa aberto em tela cheia.
- **Telas**: um monitor inteiro.
- **Aplicativos**: uma janela só, como o navegador, um editor ou um jogo em janela.
- **Resolução e FPS**: o padrão é 1080p a 60 fps. Mesmo com o jogo rodando a 120 fps ou mais, a live nunca passa do FPS escolhido. Se a internet de quem transmite for fraca, use 720p ou 30 fps.
- **Áudio**: transmitindo um **jogo ou aplicativo**, "Som deste app" manda só o som dele: música, chamada e outros programas ficam de fora. Transmitindo a **tela inteira**, "Som do PC (sem o Discord)" manda todo o som do computador, menos o do próprio Charretecord. Nos dois casos as vozes da chamada e as lives que você está assistindo ficam de fora, então ninguém ouve eco.

Qualquer outro caminho do Discord que iniciaria uma transmissão (o botão de transmitir um jogo detectado, o menu de transmissões, um pedido de transmissão) também abre o Charrete Live. Quando alguém abre uma live, a sala ouve um berro de bode bem baixinho.

### Jogos detectados

- Quando você abre um jogo durante a chamada, aparece a notificação "Transmitir jogo?".
- O atalho **Ctrl + Shift + F9** inicia ou para a live de qualquer lugar, até de dentro do jogo. Ele não pergunta nada: transmite o **aplicativo em foco** (a janela em que você está), com a resolução, o FPS e o áudio que você escolheu da última vez no seletor. Se o foco estiver no próprio Charretecord, ele transmite a tela onde está o mouse. Veja também [Atalhos](#10-atalhos-do-teclado-e-do-mouse).

> [!TIP]
> Nos jogos, prefira o modo **tela cheia sem bordas** (borderless). Na tela cheia exclusiva, dar Alt+Tab pode deixar a live preta.

## 5. Durante a live

- Quando a live abre, toca o berro de bode, o mesmo que os outros da chamada ouvem.
- A linha **Charrete Live** (acima dos botões de voz) mostra **AO VIVO**, o que você está transmitindo, quantos estão assistindo e o botão vermelho **Encerrar**. O mini player também tem **⏹ Encerrar sua live**.
- O botão de compartilhar tela fica **aceso**. Clicar nele **encerra** a live. A setinha ao lado dele **troca a fonte** (outra tela, janela ou jogo) **sem derrubar** quem está assistindo, e na troca dá para ligar ou desligar o áudio.
- A sua live aparece com o selo **SUA LIVE**, para você conferir o que os outros estão vendo. No quadro dela:
  - **⏹** encerra a live;
  - **🔄** troca a fonte;
  - **✕** só esconde a prévia (a live continua). Para ver de novo, clique no **AO VIVO** ao lado do seu nome na lista de voz.
- O atalho Ctrl + Shift + F9 também encerra.

## 6. Assistir

<img align="right" src="guia/chachan/coracao.png" width="110" alt="Cha-chan com um coração">

Quem está transmitindo aparece com o selo **AO VIVO** ao lado do nome, na lista do canal de voz. Enquanto você transmite, quem está assistindo a **sua** live aparece com um **olhinho**.

Quem usa o Charretecord aparece com o **ícone do Charretecord** (a cabra de óculos) à direita do nome e das tags, logo antes do **AO VIVO**, na chamada e na lista de membros, mesmo usando outra senha de sala. Só quem tem o Charretecord vê esse ícone. Para isso, cada app anuncia apenas um código embaralhado do ID da conta do Discord: nenhum IP ou outro dado vai junto. Os IPs continuam indo só para quem tem a mesma senha de sala, e só na hora de assistir uma live.

### Prévia ao passar o mouse

Passe o mouse em cima de quem está ao vivo para ver o que está sendo transmitido. Clique no quadro ou em **Assistir live** para abrir.

<img src="guia/previa.png" width="600" alt="Lista do canal de voz com Bruno ao vivo e o cartão da prévia mostrando Jogo de Aventura e o botão Assistir live">

Também dá para clicar direto no selo **AO VIVO**, ou dar duplo clique no nome.

### Na chamada (padrão)

As lives e câmeras aparecem como quadros na **grade de vídeo da chamada**, ao lado das pessoas, como o Go Live do Discord:

<img src="guia/grade.png" width="700" alt="Grade da chamada com Ana, Bruno e Carla, a live do Bruno, a câmera da Carla e a live do Davi com o botão Assistir live">

- Ao abrir uma live (pela lista de voz, pela prévia ou pelo selo **AO VIVO**), o Charretecord vai direto para a tela da chamada.
- Lives que você ainda não abriu aparecem com o botão **Assistir live**. O **✕** no canto esconde esse quadro.
- **Clique** numa live ou câmera para **expandir**, igual a clicar numa pessoa da chamada: ela fica grande, e as pessoas e as outras lives vão para a faixa de baixo. Clique nela de novo para voltar à grade. Abrir uma live pela grade já expande ela.
- Com uma pessoa expandida, as lives e câmeras aparecem na faixa de baixo junto com as fotos, e um clique nelas troca o destaque.
- **Duplo clique** num quadro coloca a live em tela cheia.
- **Botão direito** num quadro abre o menu da pessoa que está transmitindo, igual ao de clicar nela na chamada (volume, silenciar, perfil...).
- Funciona com "Mostrar participantes sem vídeo" desligado: se tiver live ou câmera do Charrete Live, a grade continua aparecendo.
- Saindo da chamada (por exemplo, abrindo um canal de texto), o que você está assistindo continua num **mini player** no canto da tela. Clique nele para voltar para a chamada.

### Janela separada (legacy)

Se preferir o jeito antigo, mude **Onde mostrar as lives e câmeras** para **Janela separada** nas opções. As lives abrem num **palco** em cima do chat, com grade própria:

<img src="guia/palco-grade.png" width="664" alt="Palco com três lives em grade: a sua, a do Bruno e a da Carla">

*Em grade, todas as lives ficam do mesmo tamanho.*

<img src="guia/palco-destaque.png" width="664" alt="Palco com a live do Bruno em destaque e as outras em miniatura embaixo">

*Clique numa live para deixá-la em destaque, e as outras viram miniaturas. Para voltar à grade, clique de novo na live ou use o botão ▦. No topo do palco, **▴** recolhe sem parar as lives e **✕** fecha todas. Arraste a borda de baixo para mudar a altura.*

### Controles de cada live

Passe o mouse em cima de uma live para ver os controles e as estatísticas da conexão (tipo de conexão, resolução, FPS, velocidade e atraso):

<img src="guia/quadro-controles.png" width="317" alt="Live com a barra de controles: volume, mudo, destaque, miniplayer, tela cheia e fechar">

| Botão | O que faz |
|---|---|
| Volume e 🔊 | Ajusta ou silencia o som da live. Só aparecem quando a live tem som. |
| ＋ | **Amplificar**: para quem transmite com o som baixo. Cada clique aumenta o som dessa live (2x, 3x, 4x), e mais um clique volta ao normal. Um limitador evita que o som estoure. Vale só para essa live e só no seu PC; o volume padrão não muda. |
| ⤢ | Só na janela separada: coloca a live em destaque (o mesmo que clicar nela). |
| ⧉ | **Miniplayer**: uma janelinha flutuante que fica por cima de tudo, até de jogos sem bordas. |
| ⛶ | Entra na tela cheia. O mesmo botão sai dela, e duplo clique ou Esc também saem. |
| ✕ | Para de assistir essa live. Ela some da tela até você abrir de novo pelo AO VIVO. |
| ⏹ e 🔄 | Só na sua live: encerra, ou troca o que você está transmitindo. |

## 7. Câmera

O botão de **câmera** do Discord (no painel "Voz conectada" ou na barra da chamada) liga a câmera pelo Charrete Live, direto de PC para PC, em 720p.

- A câmera de quem ligar aparece **sozinha** para todos na chamada, com o selo verde **CÂMERA**. Para não abrir sozinha, desligue **Mostrar câmeras automaticamente** nas opções: aí ela aparece com o botão **Ver câmera**.
- A sua aparece espelhada, com o selo **SUA CÂMERA**. O **✕** nela desliga a câmera.
- Dá para transmitir a tela e ficar com a câmera ligada ao mesmo tempo.
- Quem usa o Discord normal (sem Charretecord) não vê a sua câmera.

## 8. Pedir live

Passe o mouse em alguém da chamada que não está transmitindo e use o botão de **pedir transmissão** do cartão. O pedido vai pelo Charrete Live: a pessoa recebe a notificação "Fulano pediu para você abrir uma live", e clicar nela abre o seletor de transmissão.

Para quem não usa o Charretecord, o botão continua mandando o pedido normal do Discord.

## 9. Soundboard

<img align="right" src="guia/chachan/musica.png" width="110" alt="Cha-chan ouvindo música">

Toque os seus próprios sons para quem está na chamada com você. Na chamada, clique no botão com o **rosto da Cha-chan**, ao lado do botão de soundboard do Discord, no painel de voz (ou em Configurações → Plugins → CharreteLive → **Abrir a soundboard**).

- O botão abre um painelzinho com os seus sons: **clique num som** para tocar. **Ver todos** abre a janela completa.
- A Charrete Soundboard tem **só os sons que você enviou**. Na janela completa, clique em **＋ Adicionar som**: mp3, ogg, wav… de até **15 segundos**. Os arquivos ficam **só no seu PC**: ninguém recebe o arquivo, só ouve o som enquanto ele toca.
- **Clique num som** para tocar. Ele vai como áudio ao vivo para quem está **no mesmo canal de voz**, com o Charretecord e a **mesma senha de sala**. Quem usa o Discord normal não ouve.
- Toca **um som por vez**, e o próximo só depois de **2 segundos** do fim do anterior.
- **Editar sons**: renomeie, reordene (↑ ↓), apague (🗑) ou dê **reforço** de 1,5x a 4x a um som que ficou baixo.
- **Atalhos**: em **Atalhos do teclado**, crie as ações **"Charrete Soundboard: som 1"** a **"som 12"**. O número é a posição do som na lista. Em jogos que rodam como administrador, talvez seja preciso abrir o Charretecord como administrador.

**Ouvindo a soundboard dos outros:**

- O volume das soundboards é **separado do microfone** das pessoas: Configurações → Plugins → CharreteLive → **Volume das soundboards**.
- **Quem está tocando**: enquanto alguém toca um som, o nome do som aparece em verde ao lado do nome da pessoa na lista de voz.
- Para **baixar ou silenciar a soundboard de uma pessoa**, clique nela com o botão direito → **Volume da soundboard** ou **Silenciar a soundboard**.
- Para **nunca ouvir soundboards**, desligue **Ouvir a soundboard dos outros** nas mesmas opções.

## 10. Atalhos do teclado e do mouse

Em Configurações → **Atalhos do teclado** (a tela do próprio Discord), dá para criar atalhos para qualquer ação, inclusive estas do Charrete Live:

- **Charrete Live: iniciar ou parar a live**
- **Charrete Live: escolher o que transmitir**
- **Charrete Live: parar a live**

Os atalhos funcionam **em qualquer janela**, até com um jogo em tela cheia aberto ou em outro monitor (para jogos que rodam como administrador, veja abaixo). Isso vale também para as ações de segurar, como falar ao pressionar.

- **Tecla exata:** o atalho guarda a tecla que você apertou. **Ctrl esquerdo** e **Ctrl direito** (e também Shift e Alt) são atalhos diferentes, e os **números do numpad** são diferentes dos números de cima do teclado. Atalhos gravados antes da 1.6.19 aceitam os dois lados; grave de novo para separar.
- **Botões do mouse:** na hora de gravar o atalho, aperte o botão do **meio**, **voltar** ou **avançar** do mouse, sozinho ou com Ctrl, Shift ou Alt.
- **Jogos que rodam como administrador** (por exemplo Where Winds Meet): o Windows não entrega o teclado a programas comuns enquanto um desses jogos está em foco. Para os atalhos funcionarem dentro deles, talvez você precise abrir o Charretecord como administrador: clique com o botão direito no atalho do Charretecord → **Executar como administrador**. Quando o Charretecord vê um jogo assim, mostra um aviso.
- O atalho próprio do plugin (**Ctrl + Shift + F9**) continua valendo e pode ser mudado ou desligado nas opções.

## 11. Volume de voz dos amigos

<img align="right" src="guia/chachan/carinho.png" width="110" alt="Cha-chan animada">

O Charretecord vem com o volume de voz liberado até **1000%** (no Discord, o máximo é 200%). Durante a chamada, clique com o botão direito no amigo → **Volume do usuário** e arraste além dos 100%.

Para mudar esse limite, vá em Configurações → Charretecord → Plugins → **VolumeBooster**.

## 12. Atualizações

<img align="right" src="guia/chachan/comemorando.png" width="110" alt="Cha-chan comemorando">

Clique no **⟳** da barra do topo (no canto direito, depois do botão de ajuda) ou no ⟳ da linha Charrete Live. Também dá para ir em Configurações → Plugins → CharreteLive → **Procurar atualizações**. Quando sai versão nova, aparece uma notificação "Charretecord: nova versão" (clique nela para atualizar), e os dois ⟳ ficam verdes; o da barra do topo também ganha uma bolinha. O Charretecord confere a cada 30 minutos.

Depois de atualizar, abre a janela de **Novidades**: na primeira vez ela mostra tudo o que o Charretecord tem; depois, só o que mudou. Para ver de novo, use Configurações → Plugins → CharreteLive → **Novidades do Charretecord**, ou leia o [histórico completo](NOVIDADES.md).

<img src="guia/atualizacoes.png" width="480" alt="Janela Atualizações do Charretecord com as versões do Charretecord, Vesktop e Vencord">

- Quando há versão nova, o botão vira **Atualizar para x.y.z**. Ao clicar, o app baixa a versão nova, fecha, troca os arquivos e abre de novo. Na versão portátil, a pasta `Data` (com o seu login) é mantida.
- Quando a atualização termina, toca um **berro de bode** e aparece o aviso "Charretecord atualizado".
- O app também confere sozinho a cada 3 horas e pergunta se você quer atualizar.
- **Vesktop** e **Vencord** são a base do app. As novidades deles chegam na próxima versão do Charretecord.

> [!IMPORTANT]
> As primeiras versões não tinham o botão ⟳. Se o seu painel do Charrete Live mostra "sinalização" no lugar de "sala XXXX", baixe e instale a versão mais recente pela [página de versões](https://github.com/Augusto-ALN/charretecord-releases/releases/latest). Depois disso, as atualizações chegam sozinhas.

## 13. Problemas comuns

<img align="right" src="guia/chachan/brava.png" width="110" alt="Cha-chan brava">

| O que acontece | Causa provável | O que fazer |
|---|---|---|
| Bolinha vermelha, "0/3" | A rede bloqueia a conexão que os PCs usam para se encontrar. É comum em redes de empresa ou faculdade e com antivírus rígido. | Teste em outra rede (por exemplo, com a internet do celular). Se funcionar, o problema é a rede. |
| Não vejo a live de ninguém | Senha da sala diferente, versões diferentes do Charretecord (todos precisam estar na 1.7.7 ou mais nova), ou vocês estão em canais de voz diferentes. | Compare o código `sala XXXX` na linha Charrete Live. Se for diferente, cole a senha de novo. Entrem no mesmo canal, ou usem o modo "Sempre". |
| Aviso "O relógio deste PC está X min adiantado/atrasado" | A data ou a hora do Windows está errada. | Nas configurações do Windows, vá em Hora e idioma e ligue **Definir horário automaticamente**. |
| A live de um amigo fica sempre em "conectando" e ele não tem o botão ⟳ | Ele está numa versão antiga, que não conversa com as novas. | Ele precisa baixar e instalar a versão mais recente uma vez. Veja [Atualizações](#12-atualizações). |
| A live aparece, mas fica em "conectando" | A rede de um dos dois não permite conexão direta. Acontece com alguns tipos de CGNAT, 4G/5G ou firewall. Deixar o IPv6 ligado no Windows costuma resolver. | Se não resolver, é preciso configurar um servidor TURN nas opções do plugin. Peça para quem cuida do Charretecord. |
| Live preta ou parada no jogo | Jogo em tela cheia exclusiva. | Use o modo "tela cheia sem bordas" no jogo. |
| Imagem travando em cenas pesadas do jogo | O jogo está usando a placa de vídeo inteira. | Durante a live, o Charretecord pede prioridade de tempo real na placa de vídeo (na NVIDIA, alta) e impede o Windows de pôr o app em modo eficiência quando o jogo cobre a janela. Quando falta força, a live prefere perder um pouco de nitidez a perder quadros. Em jogos que pesam muito no processador, uma live a **60 FPS** pode não ter folga: teste a live a **30 FPS** no seletor. Também ajuda desligar gravadores em segundo plano (Instant Replay da NVIDIA, gravação do Xbox Game Bar) e usar o jogo em **tela cheia sem bordas**. |
| Imagem borrada | O upload de quem transmite está no limite, porque cada espectador recebe uma cópia da live. | Baixe para 720p ou 30 fps no seletor. Passe o mouse na linha Charrete Live para ver o que está limitando. |
| Ninguém ouve o som do jogo | A live foi iniciada com "Sem áudio". | Use a setinha do botão de transmitir para trocar a fonte e ligue o áudio ("Som deste app" numa janela, "Som do PC (sem o Discord)" na tela inteira). |
| Atalho não funciona dentro do jogo | Versão anterior à 1.6.19, ou o jogo roda como administrador. | Atualize pelo ⟳. Se o jogo roda como administrador (como o Where Winds Meet), abra o Charretecord como administrador: botão direito no atalho dele → **Executar como administrador** (veja [Atalhos](#10-atalhos-do-teclado-e-do-mouse)). |

## 14. Todas as opções

Ficam em Configurações → Charretecord → Plugins → **CharreteLive**:

| Opção | O que faz | Padrão |
|---|---|---|
| Senha da sala | Precisa ser igual em todos os PCs do grupo. Só quem tem a senha vê e assiste às lives. Mínimo de 12 caracteres, misturando letras, números ou símbolos. Só vale depois de clicar em **Aplicar** (até 5 trocas a cada 10 minutos). | vazia |
| Gerar senha forte | Cria uma senha aleatória, coloca no campo e copia para você mandar aos amigos. Clique em **Aplicar** para usar. | |
| Onde as lives aparecem | Só para quem está no mesmo canal de voz, ou sempre. | Mesmo canal |
| Onde mostrar as lives e câmeras | Na grade de vídeo da chamada, ou numa janela separada acima do chat (legacy). | Na chamada |
| Upload máximo das lives | Soma do que vai para todos os espectadores, dividida entre eles. Cada um recebe uma cópia da live pelo seu upload; se ele enche, a sua voz trava para os outros na chamada. Aumente se a sua internet tiver upload de sobra. | 10 Mbps |
| Som quando alguém entra na sua live | Toca o mesmo som do Discord quando alguém começa a assistir. | Ligado |
| Ouvir a soundboard dos outros | Desligado, nunca toca a soundboard de ninguém. | Ligado |
| Volume das soundboards dos outros | Volume dos sons das soundboards, separado do microfone das pessoas. | 70% |
| Mostrar câmeras automaticamente | A câmera de quem ligar aparece sozinha. Desligado, aparece com o botão "Ver câmera". | Ligado |
| Atalho | Tecla global para iniciar e parar a live. Deixe vazio para desligar. | Ctrl+Shift+F9 |
| Ação do atalho | Transmitir o aplicativo em foco sem perguntar, sempre abrir o seletor, ou repetir a última fonte. | Aplicativo em foco |
| Resolução e FPS | A qualidade que já vem marcada no seletor. | 1080p, 60 fps |
| Bitrate máximo | Limite de velocidade do vídeo, em kbps. Com 0, o app decide pela resolução. | 0 (automático) |
| Codec | Formato do vídeo. O automático usa H.264 pela placa de vídeo. | Automático |
| Áudio por padrão | Se o seletor já abre com o som do PC marcado. | Ligado |
| Máximo de espectadores | Quantas pessoas podem assistir à sua live (e à sua câmera). Cada uma usa parte do seu upload. | 5 |
| Detectar jogos | Reconhece jogos e programas abertos em tela cheia. | Ligado |
| Notificar jogo | Mostra "Transmitir jogo?" quando um jogo abre durante a chamada. | Ligado |
| Brokers, STUN e TURN | Servidores de encontro e de conexão. Só mexa se alguém do grupo pedir. | já configurados |

---

<sub>As imagens deste guia foram feitas com contas e vídeos de exemplo. Client mods violam os Termos de Serviço do Discord: use por sua conta e risco.</sub>

## 15. Cha-chan

<img align="right" src="guia/chachan/hamburguer.png" width="120" alt="Cha-chan comendo um hambúrguer">

A **Charrete-chan**, ou só **Cha-chan**, é a mascote do Charretecord. Ela aparece ao lado do nome de quem usa o Charretecord, nas notas de atualização e no botão com o rosto dela na **barra do topo**, que abre a janela dela.

**Ela é um bichinho virtual:**

- Para continuar viva, ela precisa de você no Charretecord, logado, **pelo menos 30 minutos por dia**. O dia em que ela chega não conta. Se um dia ficar abaixo disso, ela se vai, e dá para adotar outra.
- A **barriga** e a **felicidade** caem com o tempo. **Hambúrguer** enche a barriga. **Cerveja** deixa ela feliz (até 3 por dia).
- O botão dela na barra do topo ganha um aviso quando ela está com fome, carente ou quando ainda faltam minutos no dia (a partir das 20h).

<img align="right" src="guia/chachan/cerveja.png" width="110" alt="Cha-chan tomando cerveja">

**Na área de trabalho:**

- Na janela dela, clique em **Soltar na área de trabalho**. Ela passeia pela tela, sobe em cima das janelas abertas e vai junto quando você arrasta a janela em que ela está.
- **Clique** nela para fazer carinho. **Arraste** para levar para outro lugar (ou jogar longe). **Botão direito** para dar hambúrguer, cerveja ou guardar. **Dois cliques** abrem a janela dela.
- Ela fica na frente de tudo, até de jogos e vídeos em tela cheia (modo janela sem bordas). Para tirar da tela, use **Guardar a Cha-chan**.
- As partes transparentes em volta dela não atrapalham: o clique passa para a janela de baixo.

<img align="right" src="guia/chachan/dormindo.png" width="140" alt="Cha-chan dormindo">

**Em breve:** skins novas para a Cha-chan, liberadas conforme o tempo de vida dela.

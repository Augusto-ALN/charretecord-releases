<p align="center"><img src="guia/novidades/capa.png" width="900" alt="Notas de atualização do Charretecord"></p>

# Novidades do Charretecord

O que o Charretecord tem de diferente do Discord e o histórico de tudo o que mudou em cada versão. Dentro do app, a janela de novidades abre sozinha depois de cada atualização (e em Configurações → Plugins → CharreteLive → **Novidades do Charretecord**).

## A mais que o Discord

<table>
<tr>
<td><img src="guia/novidades/lives.png" width="430" alt="Lives até 4K 60 FPS, sem Nitro"></td>
<td><img src="guia/novidades/privadas.png" width="430" alt="Lives privadas, de PC para PC"></td>
</tr>
<tr>
<td><img src="guia/novidades/soundboard.png" width="430" alt="Soundboard sem Nitro"></td>
<td><img src="guia/novidades/voz.png" width="430" alt="Volume de voz até 1000%"></td>
</tr>
<tr>
<td><img src="guia/novidades/amplificar.png" width="430" alt="Amplificar o som de uma live"></td>
<td><img src="guia/novidades/atalho-live.png" width="430" alt="Live num atalho, sem perguntar"></td>
</tr>
<tr>
<td><img src="guia/novidades/icone.png" width="430" alt="Quem usa o Charretecord"></td>
</tr>
</table>

## No Brasil

Desde 12/08/2026, por ordem da ANPD, as transmissões ao vivo (Go Live) do Discord estão suspensas no Brasil, e o recurso do Discord foi negado em 19/11/2026. Segundo o próprio Discord, a medida também atinge chamadas de vídeo e o compartilhamento de tela. Texto e voz continuam funcionando.

Fontes: [Agência Brasil](https://agenciabrasil.ebc.com.br/radioagencia-nacional/geral/audio/2026-11/anpd-rejeita-recurso-do-discord-e-mantem-lives-suspensas-no-pais), [Olhar Digital](https://olhardigital.com.br/2026/11/19/internet-e-redes-sociais/anpd-nega-recurso-do-discord-e-mantem-lives-suspensas-no-brasil), [Carta Capital](https://www.cartacapital.com.br/toquetec/discord-suspende-recursos-de-video-no-brasil-apos-determinacao-da-anpd/).

<table>
<tr>
<td><img src="guia/novidades/br-lives.png" width="430" alt="Lives funcionando no Brasil"></td>
<td><img src="guia/novidades/br-camera.png" width="430" alt="Câmera e tela de volta"></td>
</tr>
</table>

## Notas de atualização

### 1.7.12 · Voz mais estável

<sub>25/11/2026</sub>

*A voz da chamada fica mais estável com jogos abertos e durante as lives.*

#### Melhorias

- Durante as chamadas de voz, o Windows não coloca mais o Charretecord em modo eficiência, evitando cortes na sua voz quando há um jogo em primeiro plano.
- Limite de upload das lives: a soma do que vai para todos os espectadores fica em até 10 Mbps por padrão, dividida entre eles e reajustada quando alguém entra ou sai, preservando a qualidade da sua voz na chamada. Ajustável em Plugins → CharreteLive.
- Ao fim da chamada ou da live, os ajustes de energia do Windows voltam exatamente ao estado anterior.

### 1.7.11 · Áudio de voz e desempenho

<sub>25/11/2026</sub>

*Áudio da chamada mais estável e menor uso de memória fora das chamadas.*

#### Novidades

- Reiniciar o áudio desta pessoa: no menu de contexto de alguém da chamada, recria o áudio dela na hora, sem sair da chamada.

#### Melhorias

- Recuperação automática do áudio de cada participante: se o som de alguém parar, ele volta sozinho em poucos segundos.
- Volume de voz acima de 100% mais estável: o dispositivo de saída de áudio não é mais reconfigurado a cada atualização.
- Menor uso de memória: a detecção de jogos só funciona durante as chamadas (cerca de 80 MB a menos fora delas), e a soundboard mantém na memória apenas os últimos sons tocados.

### 1.7.10 · Atualização de segurança

<sub>23/11/2026</sub>

*Proteção reforçada para salas, senhas e atualizações, e compartilhamento de acesso sem revelar a senha. O grupo precisa estar na 1.7.7 ou mais nova para continuar se vendo nas lives, e compartilhar acesso exige a 1.7.10 nos dois computadores.*

#### Segurança

- Derivação de chave reforçada para a senha da sala: cada tentativa de adivinhação ficou cerca de 60 mil vezes mais cara.
- Identificador da sala ampliado para 256 bits e protegido contra injeção. As mensagens ficam vinculadas à sala e expiram em 5 minutos.
- Atualizações assinadas digitalmente: o aplicativo só instala versões assinadas pelo Charretecord, e somente após a sua confirmação.
- Limite de trocas da senha da sala (5 a cada 10 minutos) contra tentativas em sequência.
- Acesso compartilhado cifrado de ponta a ponta e guardado com a proteção do Windows: a senha nunca sai do computador de quem compartilha.

#### Novidades

- Compartilhar acesso à sala: clique com o botão direito em alguém do seu canal de voz para dar acesso à sua sala sem revelar a senha. Vocês passam a ver as lives um do outro, e os dois conferem um código antes de concluir.
- Campo de senha com botão Aplicar: a senha só passa a valer quando você confirma.
- Gerador de senha forte, que cria e copia uma senha aleatória para compartilhar com o grupo.
- Permissão de recompartilhar: ao compartilhar o acesso, você escolhe se a pessoa também pode compartilhar com outras. Só quem tem a senha concede essa permissão.

#### Melhorias

- Requisito mínimo de senha: 12 caracteres, combinando letras, números ou símbolos.
- Limites para as solicitações de cada participante da sala. Apenas as lives que você abrir podem ser assistidas.
- Fora da chamada, nenhuma conexão com a sala é mantida. No modo Sempre, câmeras só abrem automaticamente para quem está no seu canal de voz.
- Código da sala com 8 caracteres, para conferir com mais segurança se todos usam a mesma senha.
- Convites de acesso mais confiáveis: o convite é reenviado até o outro app responder, e um aviso aparece em 15 segundos se não houver resposta.

### 1.7.6 · Aviso de espectadores

<sub>22/11/2026</sub>

*Aviso sonoro de novos espectadores e áudio de chamada mais estável.*

#### Novidades

- Som de entrada quando alguém começa a assistir à sua live, o mesmo do Discord. Pode ser desativado em Plugins → CharreteLive.

#### Melhorias

- Áudio de voz mais estável: até 100%, cada participante é reproduzido diretamente pelo Discord, e o reforço de volume atua somente acima disso.

### 1.7.5 · Identificação na soundboard

<sub>20/11/2026</sub>

*Saiba quem está tocando cada som e ajuste o volume por pessoa.*

#### Novidades

- Indicador na lista de voz com o nome do som que cada participante está tocando.
- Volume da soundboard por pessoa, no menu de contexto do participante, além da opção de silenciar.

### 1.7.4 · Painel da soundboard

<sub>20/11/2026</sub>

*Acesso rápido aos seus sons direto do painel de voz.*

#### Melhorias

- Painel compacto acima do botão da soundboard, no padrão do Discord: um clique toca o som, e Ver todos abre o gerenciamento.

#### Correções

- Ícone do botão da soundboard centralizado.
- Notas de atualização exibidas corretamente após atualizar, aguardando o carregamento completo do Discord.

### 1.7.3 · Soundboard no painel de voz

<sub>20/11/2026</sub>

*Novo ponto de acesso à Charrete Soundboard e gerenciamento de sons redesenhado.*

#### Novidades

- Botão da Charrete Soundboard no painel de voz, ao lado da soundboard do Discord.

#### Melhorias

- Biblioteca de sons em grade, com edição de nome, ordem, reforço e exclusão.
- Acesso à soundboard centralizado no painel de voz, fora da linha Charrete Live.

### 1.7.2 · Notas de atualização revisadas

<sub>20/11/2026</sub>

*Apresentação mais clara dos recursos exclusivos e do cenário no Brasil.*

#### Melhorias

- Janela de novidades focada nos recursos exclusivos do Charretecord, com seção dedicada ao Brasil.

#### Correções

- Limite de volume de voz informado corretamente: até 1000%.

### 1.7.1 · Charrete Soundboard

<sub>20/11/2026</sub>

*Soundboard própria, sem Nitro, e base atualizada para o Vesktop 1.7.0.*

#### Novidades

- Charrete Soundboard: sons de até 15 segundos, armazenados no seu computador e transmitidos ao vivo para a chamada.
- Controle de áudio da soundboard: volume próprio, silenciamento por pessoa e opção para desativar os sons recebidos.
- Atalhos de teclado para até 12 sons.
- Janela de novidades com o histórico de versões.

#### Melhorias

- Base atualizada para o Vesktop 1.7.0.
- Orientação sobre atalhos em jogos executados como administrador.

### 1.6.31 · Amplificação de áudio da live

<sub>19/11/2026</sub>

*Mais volume para lives com áudio baixo.*

#### Novidades

- Amplificação por live (2x, 3x e 4x) com limitador, sem alterar o volume padrão.

### 1.6.30 · Nova identidade visual

<sub>18/11/2026</sub>

*Ícone de usuário do Charretecord atualizado.*

#### Melhorias

- Novo ícone de usuários do Charretecord, exibido ao lado do nome e das tags.

### 1.6.29 · Identificação de usuários

<sub>18/11/2026</sub>

*Veja quem também usa o Charretecord.*

#### Novidades

- Ícone de usuário do Charretecord na lista de voz e de membros, independente da senha de sala. Nenhum endereço IP é compartilhado.

### 1.6.28 · Codificação por hardware

<sub>18/11/2026</sub>

*Mais desempenho na transmissão.*

#### Melhorias

- Perfis H.264 High e Main, priorizando o codificador da placa de vídeo.
- Prioridade de processamento elevada para a captura durante a live.

### 1.6.27 · Desempenho em jogos

<sub>18/11/2026</sub>

*Lives mais fluidas durante jogos exigentes.*

#### Melhorias

- Prioridade de GPU em tempo real durante a live e preferência por fluidez em vez de nitidez.

#### Correções

- Taxa de quadros da captura mantida com o aplicativo em segundo plano: 30 FPS estáveis e até cerca de 49 FPS no modo 60.

### 1.6.26 · Controles da visualização expandida

<sub>18/11/2026</sub>

*Ajustes nos controles da grade da chamada.*

#### Correções

- Controles da grade reposicionados e volume da live expandida restabelecido.

### 1.6.25 · Atalhos unificados

<sub>17/11/2026</sub>

*Todos os atalhos passam pelo mesmo mecanismo.*

#### Novidades

- Aviso para jogos executados como administrador.

#### Melhorias

- Atalho Ctrl + Shift + F9 integrado ao mesmo mecanismo dos demais atalhos.

### 1.6.24 · Visualização expandida

<sub>17/11/2026</sub>

*Foco em uma live com um clique.*

#### Novidades

- Expansão de lives e câmeras com um clique, com as demais em uma faixa inferior.
- Notificação de nova versão disponível, com destaque nos botões de atualização.

### 1.6.21 · Controles da live

<sub>17/11/2026</sub>

*Mais controle sobre lives na chamada.*

#### Novidades

- Menu de contexto do Discord nos quadros da chamada.
- Botão Encerrar na linha Charrete Live e no mini player.

#### Melhorias

- Abrir uma live leva direto à chamada, com aviso sonoro para quem transmite.

### 1.6.20 · Transmissão rápida

<sub>17/11/2026</sub>

*Comece uma live em um atalho.*

#### Novidades

- Botão de atualizações na barra superior.

#### Melhorias

- Ctrl + Shift + F9 transmite instantaneamente o aplicativo em foco, com as últimas configurações.

### 1.6.19 · Atalhos globais

<sub>17/11/2026</sub>

*Atalhos que funcionam com o aplicativo em segundo plano.*

#### Novidades

- Atalhos ativos em segundo plano, incluindo ações de pressionar e segurar, com distinção entre Ctrl esquerdo e direito e teclado numérico.

### 1.6.18 · Lives na grade

<sub>17/11/2026</sub>

*A grade da chamada passa a ser o modo padrão.*

#### Melhorias

- Lives exibidas na grade da chamada por padrão, com a janela separada disponível como opção.

### 1.6.17 · Modos de visualização

<sub>17/11/2026</sub>

*Escolha como assistir às lives.*

#### Novidades

- Escolha entre a grade da chamada e uma janela separada, com controles para fechar e encerrar.

### 1.6.16 · Integração com a chamada

<sub>17/11/2026</sub>

*Lives e câmeras dentro da chamada do Discord.*

#### Novidades

- Lives e câmeras na grade da chamada, mini player e linha de status Charrete Live no painel de voz.

### 1.6.15 · Painel de voz

<sub>17/11/2026</sub>

*Botões do Discord direcionados ao Charrete Live.*

#### Correções

- Botões de câmera e de transmissão do painel de voz direcionados ao Charrete Live.

### 1.6.14 · Prévia e solicitação de live

<sub>17/11/2026</sub>

*Veja antes de entrar e peça uma live.*

#### Novidades

- Prévia ao passar o mouse sobre quem está ao vivo e solicitação de live integrada.

### 1.6.13 · Substituição do Go Live

<sub>17/11/2026</sub>

*O Charrete Live assume as transmissões e a câmera.*

#### Novidades

- Charrete Live no lugar do Go Live e da câmera do Discord, com indicador AO VIVO e câmera ponto a ponto.

### 1.6.12 · Login e atalhos de mouse

<sub>17/11/2026</sub>

*Login mais simples e novos atalhos.*

#### Novidades

- Atalhos com os botões do mouse (meio, voltar e avançar).

#### Correções

- Login sem a solicitação indevida de chave de segurança do Windows.

### 1.6.11 · Prioridade de GPU

<sub>16/11/2026</sub>

*Transmissão mais estável sob carga.*

#### Melhorias

- Prioridade de GPU elevada durante a live e respeito ao limite de FPS na captura.

### 1.6.10 · Codificação H.264

<sub>16/11/2026</sub>

*Codificação por hardware como padrão.*

#### Novidades

- Aviso sonoro quando alguém abre uma live.

#### Melhorias

- Codificação H.264 pela placa de vídeo como padrão e diagnóstico de envio.

### 1.6.8 · Atalhos do Discord

<sub>16/11/2026</sub>

*Ações do Charrete Live na tela de atalhos do Discord.*

#### Novidades

- Integração com a tela de Atalhos do teclado do Discord, incluindo ações do Charrete Live.

### 1.6.7 · Sincronização de salas

<sub>14/11/2026</sub>

*Conexão entre PCs mais tolerante.*

#### Melhorias

- Tolerância a diferenças de relógio, senha sem espaços acidentais e código de verificação da sala.

### 1.6.5 · Aviso de atualização

<sub>14/11/2026</sub>

*Confirmação sonora ao concluir uma atualização.*

#### Novidades

- Aviso sonoro ao concluir uma atualização.

### 1.6.4 · Lançamento

<sub>14/11/2026</sub>

*Primeira versão pública do Charretecord.*

#### Novidades

- Lives ponto a ponto dentro do Discord, aplicativo dedicado com instalador e versão portátil, e atualizações integradas.

---

As versões 1.6.0 a 1.6.3 foram builds de teste, e as 1.6.9, 1.6.22 e 1.6.23 tiveram mudanças desfeitas na versão seguinte. As versões 1.7.7 a 1.7.9 foram publicadas com parte das mudanças da 1.7.10, e as notas estão juntas.

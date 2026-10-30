---
title: Política de Privacidade da Lizian
lang: pt-BR
---
# Política de Privacidade da Lizian

**Versão 1.1** · 30 de outubro de 2026 · em vigor a partir da publicação no endereço abaixo.
Endereço desta política: https://derickbezerra.github.io/lizian-privacidade/

## 1. Quem somos e a quem esta política se aplica

A Lizian ajuda varejistas e fornecedores a entender o que está exposto nas
gôndolas das lojas: quais produtos estão lá, onde e com que preço na etiqueta.

- **Responsável pelo tratamento:** LIZ TECNOLOGIA DA INFORMACAO LTDA (microempresa), CNPJ 63.759.846/0001-20, com sede na Rua Pais Leme, 215, conjunto 1713, Pinheiros, São Paulo/SP, CEP 05424-150.
- **Papel da Lizian em cada tratamento e papel da organização cliente:** confirmado pelo fundador; documento físico com o jurídico da Lizian.
- **Encarregado pelo tratamento de dados pessoais:** confirmado pelo fundador; documento físico com o jurídico da Lizian.
- **Canal de privacidade:** bezerra@belvy.com.br, para qualquer pedido ou dúvida sobre os seus dados.

Esta política vale para:

- os aplicativos para iPhone **Lizian Captura** e **Lizian Avaliação** (a versão
  de testes, distribuída pelo TestFlight), usados pela equipe da loja para
  fotografar as gôndolas;
- o **painel web da Lizian**, usado por varejistas e fornecedores com conta. Não
  há cadastro aberto: a conta é criada por um operador da Lizian ou pelo convite
  de quem administra a loja ou a rede.

O aplicativo e o painel são ferramentas de trabalho e são destinados a
**pessoas com 18 anos ou mais**.

## 2. O princípio: produto sim, pessoa não

A Lizian existe para medir a gôndola, não para observar pessoas. Por isso:

- o aplicativo **detecta pessoas no próprio celular e cobre a área delas antes
  de a foto ser guardada**. A imagem original, com a pessoa à mostra, não é
  gravada nem enviada. No Lizian Captura a área é coberta por um retângulo
  preto; no Lizian Avaliação, por um mosaico que segue o contorno da pessoa;
- **não fazemos reconhecimento facial**, não comparamos rostos, não criamos
  identificador de rosto e não contamos, seguimos ou traçamos perfil de clientes
  ou funcionários;
- **não medimos a produtividade de pessoas**;
- não guardamos dados de clientes da loja (consumidores);
- de cada foto guardamos quantas áreas foram cobertas, só como prova de que o
  filtro agiu. Esse número não é usado para contar pessoas.

Nenhum detector é perfeito. Se o filtro dá erro, não termina a tempo ou não
consegue provar que agiu, a imagem é apagada da memória e descartada no
celular; se o filtro não está disponível, a câmera do aplicativo não abre.
Mesmo assim, se o detector não perceber uma pessoa, ela pode aparecer na foto
guardada. Nos servidores, a foto em que alguém aparece sem cobertura não é
usada para ler produtos. Se você aparecer numa foto, pode pedir que ela seja
apagada (seção 9).

**Demonstração do borrão.** O aplicativo tem uma tela "Ver o borrão ao vivo",
que mostra a câmera com as pessoas já cobertas. Nela **nada é gravado nem
enviado**: a imagem só passa pela tela e funciona sem conta e sem internet.

## 3. Que dados tratamos

### 3.1 No aplicativo

| Dado | O que é | Sai do celular? |
|---|---|---|
| Foto da gôndola | Imagem da prateleira com as pessoas já cobertas, em JPEG: quadros de até 1920 px no lado maior (no Lizian Avaliação, num modo de teste escolhido pela equipe, até 3840 px) e, em momentos escolhidos pelo app, a foto inteira da câmera (até 12 megapixels, 4032 × 3024). A imagem **não leva localização, data nem dados do aparelho** nos metadados | Sim, para os servidores da Lizian |
| Dados da foto | Horário do celular e a diferença dele para o relógio do servidor, o instante da foto dentro da caminhada, o horário em que as pessoas foram cobertas, corredor informado por quem fotografa, código de integridade (hash) e tamanho da imagem, quantas áreas foram cobertas, a versão do filtro e o motivo e o alcance da guarda | Sim |
| Localização, só para conferir que a foto foi tirada dentro da loja | Com o aplicativo aberto, o celular lê a posição para conferir se está dentro da área da loja. Junto de cada foto vão a posição do momento e a última posição boa, com a precisão e o horário da leitura. **No servidor, a posição é usada só para essa conferência e descartada; guardamos apenas o resultado ("dentro" ou "incerta") e a precisão da leitura, em metros.** Não acompanhamos o seu caminho e não lemos a posição com o aplicativo fechado | Sim, para a conferência; o servidor não guarda a posição |
| E-mail e senha de quem liga o celular à loja | Quem responde pela loja entra uma vez com o e-mail e a senha da conta Lizian para ligar o celular a ela. A senha só passa pela conexão segura; o celular não guarda a senha nem o e-mail. A sessão é encerrada logo depois; se a rede cair nesse momento, ela vence sozinha em até 7 dias. O celular guarda o nome da loja | Sim, para entrar |
| Dados do aparelho | A parte pública de uma chave criada pelo aplicativo para assinar os envios, um contador de envios, o sistema (iOS) e a versão e o número do build do aplicativo. **O nome que você deu ao celular nunca é enviado**, e o modelo do iPhone também não | Sim |
| Dados da caminhada | Início e fim da caminhada, identificadores aleatórios dela criados no celular, leituras do relógio do celular (para acertar os horários), o corredor informado e a lista de corredores percorridos. Ficam ligados ao aparelho e à loja, não a quem fotografou | Sim |
| Situação da fila de envio | Só contagens e faixas de idade das fotos que esperam envio | Sim |
| Aviso de falha da proteção | Se a proteção de privacidade não carregar no celular, o app avisa o servidor, com o horário | Sim |
| Movimento | O sensor de movimento serve para saber, no celular, quando você está caminhando no corredor e ligar a captura nessa hora (no Lizian Avaliação, também entra no registro técnico abaixo) | **Não** |

O envio não leva o nome de quem fotografou: o celular é ligado à loja, não à
pessoa que o usa.

O aplicativo **não** coleta: áudio, contatos, fotos da sua galeria, biometria
(Face ID ou digital) nem identificador de publicidade. Não tem anúncios nem
ferramentas de análise de uso ou de falhas de terceiros. O único serviço de
terceiro que ele consulta é o de atualizações da Expo (seção 5). O envio das
fotos em segundo plano usa o serviço de transferência do próprio iOS, direto
para os servidores da Lizian.

Ficam no armazenamento do aplicativo no celular: as fotos que esperam envio
(já com as pessoas cobertas), com as leituras de posição que as acompanham; a
chave do aparelho e os identificadores do aparelho, da organização e da loja;
o nome e o ponto da loja no mapa; e um diário da caminhada (horários,
corredores e contagens). Tudo isso pode entrar no backup do aparelho (iCloud
ou computador), se o dono do celular fizer backup.

**Registro técnico do Lizian Avaliação.** Só na versão de testes, o aplicativo
guarda também no celular um registro técnico da câmera e do aparelho: movimento
e posição do celular, exposição e lente de cada quadro, bateria, temperatura e
memória, os toques na tela (com o ponto tocado) e os códigos de barras lidos.
Não tem imagem nem dado que identifique uma pessoa e **não é enviado pela
internet**; a equipe da Lizian pode copiá-lo pelo cabo, dos celulares dela,
para análise técnica. Quem instala pelo TestFlight não passa por essa cópia.

Permissões pedidas: **câmera** (para fotografar a gôndola e para a
demonstração), **localização durante o uso** (para conferir que a foto é da
loja) e **movimento** (para ligar a captura só quando você caminha).

### 3.2 No painel web

| Dado | Para quê |
|---|---|
| E-mail (obrigatório) e nome (opcional) | Identificar a sua conta |
| Senha | Entrar. Guardamos só uma versão embaralhada (hash), nunca a senha em si |
| Sessão: endereço IP, navegador (user agent) e validade | Manter você conectado por até 7 dias e proteger a conta |
| Organização, lojas e papel | Mostrar só o que o seu papel pode ver |
| Preferências, tarefas, acompanhamentos e relatórios que você salva | Lembrar como você usa o painel |
| Perguntas feitas ao assistente do painel, quando ligado | Responder sobre os dados da sua loja (seção 5) |
| Registros de segurança: ações e consultas (quem, o quê, quando) | Segurança e prestação de contas |
| Convite: e-mail convidado, lojas, papel, quem convidou, validade (48 horas) e uso | Dar acesso só a quem foi convidado |

Não pedimos CPF, telefone, data de nascimento nem endereço pessoal. O painel
usa um único cookie, o de sessão, da própria Lizian; não usa cookies de
publicidade nem de análise.

### 3.3 Dados de empresas

Para cada organização cliente guardamos razão social, nome fantasia, CNPJ, as
lojas (nome, código, endereço e o ponto no mapa) e o e-mail de quem administra
a conta.

## 4. Para que usamos os dados e com que base legal

| Tratamento | Finalidade |
|---|---|
| Fotos da gôndola com pessoas cobertas e dados da foto | Saber que produtos, preços e espaços estão na gôndola |
| Localização durante o uso | Conferir que a foto foi tirada dentro da loja |
| E-mail e senha no app | Ligar o celular à loja de quem responde por ela |
| Dados do aparelho, fila de envio e aviso de falha | Garantir que a foto veio de um celular ligado pela loja, chegou inteira e foi protegida |
| Conta, senha e sessão do painel | Dar acesso e proteger a conta |
| Registros de segurança | Segurança, prevenção de fraude e prestação de contas |
| Recortes de produto em testes internos de IA (seção 5) | Melhorar o reconhecimento de produtos |

**Base legal (LGPD) de cada tratamento:** confirmado pelo fundador; documento
físico com o jurídico da Lizian.

**Decisões automáticas.** O sistema decide de forma automática só sobre
**produtos**: qual produto está numa posição, se a frente está vazia, qual preço
a etiqueta mostra. Nenhuma decisão automática é tomada sobre pessoas.

## 5. Com quem os dados são compartilhados

- **Dentro da sua organização:** cada pessoa vê só o que o papel dela permite. Os dados de uma organização são separados dos de outra no próprio banco de dados.
- **Fornecedores (indústria):** veem só os dados das lojas e dos produtos a que têm direito por acordo com o varejista. **O fornecedor não vê fotos**, nem quem fotografou.
- **Atualizações do aplicativo:** o aplicativo consulta o serviço de atualizações da Expo. Em cada consulta, a Expo recebe um identificador aleatório criado na instalação, o endereço IP, a plataforma e a versão do aplicativo.
- **Distribuição de testes:** quem instala o Lizian Avaliação pelo TestFlight está sujeito também à política da Apple para o TestFlight, que recebe dados de instalação e o retorno que você mandar por ele.
- **Rede privada:** os servidores da Lizian são acessados por uma rede privada da Tailscale, com conexão criptografada.
- **Mapa das lojas:** para achar o ponto de uma loja no mapa, o endereço comercial da loja (não dado de pessoa) é consultado nos serviços públicos ViaCEP e OpenStreetMap (Nominatim).
- **Assistente do painel, quando ligado:** o texto da pergunta vai a um modelo de IA de terceiro pelo serviço OpenRouter, sem foto.
- **Inteligência artificial de terceiros, só em testes internos:** para testar e melhorar o reconhecimento de produtos, a Lizian pode enviar a serviços de IA de terceiros (OpenRouter, Google Cloud Vision e Gemini, OpenAI) **apenas pedaços de foto**: o recorte de um produto ou um trecho de prateleira em volta dele, cada um com no máximo um quarto da foto, tirados de fotos em que nenhuma pessoa foi detectada nem coberta. Nunca enviamos a foto inteira, imagem com pessoa, nem identificador da loja, da organização ou de quem fotografou. Esses provedores podem estar fora do Brasil (seção 6). **No produto em uso, nenhuma foto é enviada a serviços de IA de terceiros.**
- **Autoridades:** quando a lei exigir.

Não vendemos dados pessoais.

## 6. Onde os dados ficam e transferência internacional

Hoje o produto roda num **computador dedicado da própria Lizian**, com o disco
criptografado e acesso só pela rede privada (fase de piloto). As fotos ficam num
armazenamento de arquivos nesse computador e os demais dados num banco de dados
no mesmo computador. O Lizian Avaliação envia para um ambiente separado, no
mesmo computador, com as mesmas regras. Se a hospedagem mudar para um provedor
de nuvem, esta política será atualizada antes, com o nome do provedor e o país,
e o aviso da seção 11.

Alguns serviços citados na seção 5 podem tratar dados fora do Brasil: a Expo, a
Apple (TestFlight), a coordenação da rede privada da Tailscale, o assistente do
painel e, nos testes internos, os provedores de IA. Hipóteses de transferência
internacional: confirmado pelo fundador; documento físico com o jurídico da Lizian.

## 7. Por quanto tempo guardamos

| Dado | Prazo |
|---|---|
| Foto no celular, depois que o servidor confirma o recebimento | Apagada a partir de 5 minutos após a confirmação, na próxima vez que o aplicativo estiver aberto. As leituras de posição que acompanham a foto saem junto. A cópia temporária usada no envio em segundo plano também é apagada |
| Foto no celular ainda não enviada ou recusada pelo servidor | Fica no celular até ser enviada ou até o aplicativo ser apagado |
| Registro técnico do Lizian Avaliação (no celular) | Fica no celular até o aplicativo ser apagado |
| Posição do celular no servidor | Não é guardada: usada na conferência e descartada |
| Foto da gôndola no servidor | **No máximo 30 dias** a partir do recebimento. Uma rotina automática roda de hora em hora e apaga as fotos que vencem. Se você pedir, apagamos antes (seção 9) |
| Resumo da fila de envio do aparelho | 7 dias |
| Aviso de falha da proteção | 30 dias |
| Foto preservada por ordem legal | Até o fim da obrigação |
| Informação sobre produtos lida das fotos | Enquanto a loja for cliente da Lizian |
| Conta do painel (inclusive o e-mail usado no app) | Enquanto a conta existir |
| Sessões do painel e do app (com IP e navegador) | Expiram em até 7 dias; o registro vencido é apagado 30 dias depois |
| Convites | 90 dias depois de aceitos ou vencidos |
| Registros de segurança | 6 meses |

Recortes de produto não são guardados como arquivo separado no produto: são
lidos da foto na hora e somem com ela.

## 8. Como protegemos os dados

- Cobertura de pessoas no próprio celular, antes de guardar ou enviar; se o filtro falha, a imagem é descartada.
- A memória da câmera é zerada depois de cada imagem.
- Cada envio do aplicativo é assinado por uma chave criada no celular.
- Separação dos dados de cada organização no próprio banco de dados.
- Senhas guardadas só como hash.
- Conexões do aplicativo e do painel com os servidores só por HTTPS, dentro de uma rede privada; disco dos servidores criptografado.
- Contas só por convite ou pelo operador.

## 9. Seus direitos e como pedir

Pela LGPD (art. 18), você pode pedir: confirmação de que tratamos dados seus;
acesso; correção; anonimização, bloqueio ou eliminação de dados desnecessários,
excessivos ou tratados em desconformidade com a lei; portabilidade; eliminação
dos dados tratados com o seu consentimento; informação sobre com quem
compartilhamos; informação sobre a possibilidade de não consentir; revogação do
consentimento; e revisão de decisões automatizadas. Você também pode reclamar à
Autoridade Nacional de Proteção de Dados (ANPD).

**Como pedir:** escreva para **bezerra@belvy.com.br**.
**Prazo de resposta:** até **15 dias** a partir do pedido.

**Se você apareceu numa foto da loja:** escreva para o mesmo e-mail dizendo a
loja, o dia e o horário aproximado. Apagamos as fotos daquela loja e daquele
período em que você possa aparecer, sem esperar os 30 dias, e respondemos
confirmando. Para apagar, não pedimos documento e não mostramos a foto a
ninguém.

**Excluir a sua conta:** pelo painel ("Minha conta") ou pelo e-mail acima.

## 10. Crianças e adolescentes

O aplicativo e o painel são ferramentas de trabalho para pessoas com 18 anos ou
mais. Se uma criança ou um adolescente aparecer por acaso numa foto da loja, a
área detectada é coberta no celular como a de qualquer pessoa, e o pedido de
apagamento da seção 9 vale do mesmo jeito.

## 11. Mudanças nesta política

Quando esta política mudar, avisamos com **pelo menos 15 dias de antecedência**,
antes de a nova versão valer. Cada versão tem número e data no topo.

## 12. Contato

Canal de privacidade: bezerra@belvy.com.br
LIZ TECNOLOGIA DA INFORMACAO LTDA · CNPJ 63.759.846/0001-20 · Rua Pais Leme, 215, conjunto 1713, Pinheiros, São Paulo/SP, CEP 05424-150

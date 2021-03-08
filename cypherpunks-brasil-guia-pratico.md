# O começo da jornada

Bem vindo jovem garfanhoto, depois de muito relutar, você decidiu ler sobre os princípios do movimento cypherpunk e da cripto anarquia. O caminho é longo, mas com perceverança, todos alcançaremos a sabedoria do grande Satoshi. bincadeiras à parte, conhecer a cripto anarquia é abrir a mente para os ideias de liberdade na prática.

Antes de tudo, vamos começar listando os conhecimentos que você alcançará, não necessariamente nessa leitura, para se tornar um cypherpunk. Assim como em muitos projetos internet a fora, chamaremos essa listagem de _roadmap_ e assim como na grande maioria das linguagens de programação, nossa contagem começa do zero.

## Roadmap:

0. Introdução

0.0. O que é um _cypherpunk_ ?

0.1. Por que a privacidade importa?

0.2. Libertarianismo 101

0.3. Software Livre e Open Source

0.4. O que é o Projeto Cypherpunks Brasil?


1. Privacidade e Segurança

1.0. Aviso: Você está sendo vigiado

1.1. Privacidade _vs_ Segurança

1.2. De quem eu devo me proteger?

1.3. Navegadores

1.3.0. Trackers (Rastreadores)

1.3.1. Cookies

1.3.2. Fingerprint (Impressão Digital)

1.3.3. Navegadores que protegem sua privacidade

1.3.4. Extensões para navegadores

1.4. Protegendo o seu IP

1.4.0. VPN _vs_ Tor

1.4.1. VPN

1.4.3. Tor

1.4.4. DNS

1.5. HTTPS

1.6. Motores de Busca

1.7. Email

1.7.0. PGP

1.8. Firewall

2. Linux 

2.0. Qual é o problema do Windows?

2.1. O que é o Linux, exatamente?

3. Criptologia

3.0. O que é a criptologia?

3.1. Um pouco da história da criptologia

3.2. A importância da criptografia no mundo

3.3. Criptografia Simétrica

3.4. Criptografia Assimétrica

3.5. Softwares

4. O Bitcoin


## 0. Introdução

Esses tópicos introdutórios devem familiarizar o leitor com o contexto em que o Cypherpunks Brasil foi criado e a importância desse tipo de movimento para a liberdade. Também é importante ressaltar a Ética que guia o projeto, a Ética Libertária. Esse é o mínimo ético universal e atemporal no qual o libertarianismo está firmado e também onde o projeto se sustenta. Todo o trabalho do Cypherpunks Brasil tem como objetivo final minimizar violações ao Princípio de Não-Agressão (PNA).


### O que é um _cypherpunk_ ?

Um _cypherpunk_ é qualquer indivíduo que concientemente defende o uso generalizado de criptografia robusta e tecnologia para implementar privacidade, segurança e soberania individual como via de tranformação política e civil.

O movimento _cypherpunk_ começa como movimento organizado nos anos 80 logo após a primeira publicação do artigo "New Directions in Cryptography" ("Novas direções na criptografia") por Whitfield Diffie e Martin Hellman em 1976, o ponto de partida da criptologia moderna. Até então a criptologia era exclusividade do setor bélico e das agências de inteligência, após a publicação, acadêmicos de todo o mundo passaram a desenvolver pesquisas inalgurando uma nova era nesse campo a tempos esquecido. 

Essa leva de conhecimento e descobertas ganham viés filosófico em 1985 com a publicação "Security without Identification: Transaction Systems to Make Big Brother Obsolete" ("Segurança sem identificação: Sistemas de transações para tornar o Grande Irmão obsoleto") de David Chaum. Antes disso, Chaum já havia publicado em 1982 "Computer Systems Established, Maintained, and Trusted by Mutually Suspicious Groups"("Sistemas computacionais estabelecidos, mantidos e atestados por grupos mutualmente desconfiados") com a proposta inicial do que hoje chamamos de blockchain. 

No final dos anos 80, as ideias de Chaum e outros cuminaram em um movimento organizado na forma da Lista de Email dos Cypherpunks. A lista foi fundada em 1992 por Eric Hughes, um matemático e programador, Timothy C. May, um engenheiro elétrico e notório cripto-anarquista, e John Gilmore, um libertário ativista do software livre.

Em 1994 a lista havia se tornado num espaço livre onde ideias libertárias se mesclavam a discussões técnicas sobre matemática, computação e, principalmente, criptografia.

#### Cypherpunks Clássicos

- **Adam Back**: Invertor do HashCash, um sistema para evitar spam de email que deu origem ao proof-of-work (prova de trabalho) usado no bitcoin. Co-fundador da empresa de cripto-tecnologia (BlockStream)[1].

- **David D. Friedman**: Filho do renomado economista austríaco Milton Friedman, é um importante economista e teórico anarco-captalista autor do livro "The Machinery of Freedom"("O Maquinário da Liberdade").

- **Eric Hughes**: Fundador da lista de email Cypherpunk e criador do primeiro redirecionador anônimo de emails.

- **Gregory Maxwell**: Importante desenvolvedor do Bitcoin Core, autor de importantes mudanças da rede como a BIP32 e a Prova de Solvência.

- **Hal Finney**: Criador do Reusable Proof of Work (RPW), "prova de trabalho reusável", que foi usado nas primeiras criptomoedas e hoje integra o Bitcoin. Também recebeu a primeira transação de bitcoin da história.

- **Ian Grigg**: Inventor dos (Contratos Ricardianos)[2], uma forma primitiva de contratos digitais baseados em assinaturas criptográficas.

- **Jim Bell**: É um cripto-anarquista que propôs a ideia de Mercados Anônimos de Assassinato com Bitcoin aos quais ele chamou de ("Assassination Politics")[3]. Fundador do (Jim Bell Project)[4]

- **John Gilmore**: Ativista libertário que ajudou a criar o que se tornou o protocolo DHCP e fundou a Eletronic Frountier Foundation (EFF), a maior ONG de proteção a privacidade e liberdade da Internet.

- **John Perry Barlow**: Autor da (Declaração de Independência do Cyberespaço)[5].

- **Julian Assange**: Hacker e ativista fundador do WikiLeaks, site internacional sem fins lucrativos que publica vazamentos e delações de empresas e governos. Criador da criptografia (Rubberhose)[6].

- **Nick Szabo**: Cientista da computação e criptógrafo que criou o BitGold, precursor do Bitcoin, e fez algumas das primeiras contribuições para o código do Bitcoin.

- **Paul Calder Le Roux (pseudônimo)**: Programador e ex-chefe de cartel de drogas e armas, associado a criação do TrueCrypt e o RX Limited, participando de um golpe de estado e adepto de teorias sociais próximas aos cypherpunks.

- **Phil Zimmermann**: Criador do "Pretty Good Privacy"(PGP), software de criptografia revolucionário usado até hoje em todo tipo de comunicações, e um dos mais importantes criptólogos da história.

- **Pretty Good Privacy**: Um dos desenvolvedores mais ativos do Bitcoin Core e co-fundador da BlockStream.

- **Satoshi Nakamoto (pseudônimo)**: Figura misteriosa por trás da criação do Bitcoin, vários membros da Lista de Email podem ter sido o satoshi, mas sua identidade é incerta até hoje.

- **Timothy C. May**: Engenheiro da Intel, libertário, membro fundador dos Cypherpunks e criador do "Manifesto Cripto-Anarquista" e do "Cyphernomicon". "Um espectro está rondando o mundo moderno, o espectro da cripto-anarquia." (~ Timothy C. May - Manifesto Cripto-Anarquista)[7].

- **Vinay Gupta**: Inventor do (Hexayurt)[8]

- **Wei Dai**: Programador e criptógrafo criador do B-money, um dos mais importantes predecessores do Bitcoin, e da biblioteca criptográfica Crypto++.


### Por que a privacidade importa?

> Conhecimento é poder; Conhecimento sobre si é poder sobre si. A sua informação será usada para antecipar as suas ações e manipular a forma como compra, vota, e pensa.    - whyprivacymatters.org

Desde o final da era moderna, a humanidade começou a perceber a importância da informação. A consolidação da idade moderna abriu nossos olhos para a realidade nua e crua: informação é poder. Mas poder sobre o que? Obviamente, sobre o assunto do qual se toma conhecimento. O conhecimento sobre a natureza, por exemplo, nos permitiu transforma-la e exercer domínio sobre todos os outros seres vivos. O mesmo acontece com seres humanos, quanto mais informação uma organização possui sobre você, mais fácil se torna para essa mesma organização te controlar, influenciar e manipular. 

A únia função da vigilância é anteceder a violência. Afinal, quem instalaria câmeras de segurança em uma residência caso soubesse que nem a polícia irá vir ou que não dispôe de armas para defendê-la? Um estado apenas vigia seus cidadãos se tiver intensão de usar repressão contra eles.


## Referências

- [Cryptoanarchy Wiki](https://cryptoanarchy.wiki/)
- [PrivacyTools](https://www.privacytools.io/)
- [The Crypto Paper](https://github.com/cryptoseb/CryptoPaper)
- [Wikipedia: Crypto-anarchism](https://en.wikipedia.org/wiki/Crypto-anarchism)
- [Wikipedia: Cypherpunk](https://en.wikipedia.org/wiki/Cypherpunk)
- [Z33DD's Blog](https://z33dd.github.io/Ferramentas-para-tornar-sua-vida-privada/)
- [Myth-busting Tor](https://write.privacytools.io/my-thoughts-on-security/slicing-onions-part-1-myth-busting-tor)
- [ProPrivacy](https://proprivacy.com/)
- [Guia Foca](https://guiafoca.org/)
- [The Handbook of Applied Criptography](http://cacr.uwaterloo.ca/hac/)
- [r/cripto Wiki](https://www.reddit.com/r/crypto/wiki/index)

[1](https://en.wikipedia.org/wiki/Blockstream)
[2](https://iang.org/papers/ricardian_contract.html)
[3](http://cryptome.org/ap.htm)
[4](https://jimbellproject.org/)
[5](https://www.eff.org/cyberspace-independence)
[6](https://en.wikipedia.org/wiki/Rubberhose_(file_system))
[7](https://odysee.com/@avelinomorganti:7/o-manifesto-criptoanarquista-timothy-c:e)
[8](http://hexayurt.capital/)
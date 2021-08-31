# Trabalho AP2 Protótipo - Programação Script

## Protótipo de uma lista de compras.

### Nodejs + Electron.js + Crud Simples

### Para executar: 

npm install && npm run start

ou 

no linux:

./release-builds/ListaLinux-linux-x64/ListaLinux

no windows:



### Para criar executáveis

npm install electron-packager -g

para linux:

electron-packager . ListaLinux --overwrite --asar=true --platform=linux --arch=x64 --prune=true --out=release-builds

para windows:

electron-packager . ListaWindows --overwrite --asar=true --platform=win32 --arch=ia32 --prune=true --out=release-builds --version-string.CompanyName=CE --version-string.FileDescription=CE --version-string.ProductName="Lista Windows"

### Descrição Protótipo:

Um programa de uma lista de compras com CRUD simples, que possibilita adicionar novos itens e suas quantidades, e armazena após seu fechamento atravez do localstorage.

#### Pergunta: O seu protótipo é descartável ou evolucionário? Justifique.

Resposta: Ele é protótipo evolucionário, pois como está escrito permite que se adicione novas funcionalidades além das funções já presentes sem que tenha que ser feitas muitas alterações em seu código.
 
#### Pergunta: Quais as características da linguagem escolhida fazem ela apropriada para o desenvolvimento de um protótipo? 

Resposta: Foi escolhido a linguagem javascript, que tem tipagem fraca, o que permite que se escreva o codigo de forma mais rapida sem a preocupação com os tipos dos objetos, além que os objetos podem mudar de tipo de forma muito simples, além de permiter que se interaja com o HTML, permitindo uma rapida prototipagem da interface. 

#### Pergunta: Que dificuldades você teve no desenvolvimento do protótipo?

Resposta: Uma das dificultades encontradas foi que não foi possivel criar o executavel para windows atraves de uma distro Linux, sendo necessario ou um exportar pelo proprio Windows ou atraves do Wine.

#### Pergunta: Quais as vantagens de ter um protótipo desenvolvido antes da implementação do programa efetivo?

Resposta: Possibilita ver a viabilidade dos requisitos a serem implementados, escolhendo a melhor maneira dessa implementação, e vendo se a linguagem é adequada para comprir com esses requisitos, uma vez não sendo adequada se torna mais facil pivotar o projeto de outras formas. Poupando assim tempo, recursos e agilizando o desenvolvimento, e evitando eventuais riscos que poderiam surgir no programa final que não seriam vistos se não com o uso de prototipos. 
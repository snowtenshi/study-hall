+++
title = 'Denuvo'
date = 2024-10-15T15:37:32-03:00
draft = false
tags = ['pesquisa', 'pirataria', 'software']
+++

Apenas uma explicação: esse artigo eu desenvolvi para uma apresentação para uma matéria da faculdade durante o primeiro semestre. Eu e meu grupo conseguimos explorar um tema diferente e decidimos falar um pouco sobre Denuvo. Durante minha pesquisa sobre o tema eu aprendi sobre essa cultura hacker, o que achei muito interessante. No final da apresentação acabamos entrando em debate com o professor sobre essas questões de direitos das empresas, pois tocamos no assunto de pirataria. Enfim, definitivamente é um tema complexo e mais profundo do que eu pude pesquisar e conhecer ao longo de alguns dias de pesquisa mas que acho de extrema importância para começarmos a pensar sobre as empresas que produzem software, como utilizamos esse software, como elas nos impõe maneiras de utilizar esses softwares, etc. 

# Introdução

Gestão de direitos digitais (digital rights management ou DRM) se refere aos direitos autorais reservados a produtos digitais e sua distribuição. São ferramentas capazes de proteger os produtos digitais para que os mesmos não sejam distribuídos de maneira ilegal, por meio da cópia de arquivos de uma máquina para outra.

O ato de hackear ou _crackear_ jogos de videogames consiste em burlar medidas protetivas ou de licenças dentro de um jogo. Por exemplo, ao comprar um jogo, o mesmo pode ter sua licença atribuída à máquina onde foi instalado, caso o usuário queira jogar o mesmo jogo em outra máquina, ele teria que comprá-lo novamente. Para burlar essas medidas, o código fonte do jogo precisa ser alterado. Sendo assim, empresas costumam empregar métodos de proteção para impedir o acesso ao código fonte do jogo, porém produtoras ou desenvolvedores menores não costumam ter o tempo hábil ou orçamento para fazer isso.

# Desenvolvimento

## Denuvo
**Denuvo** é uma tecnologia de antisabotagem (_anti-tamper_) produzido pela empresa Denuvo Software Solutions GmbH. O primeiro jogo a lançar com o software de antisabotagem Denuvo foi FIFA 15. Uma tecnolgia de antisabotagem funciona como uma proteção contra engenharia reversa e quebra de DRM de softwares, nesse caso voltada para jogos. 

Jogos protegidos por Denuvo necessitam de acesso a internet para validação via autenticação online, que é única para cada cópia do jogo e dependente de fatores como hardware do usuário, o que dificulta a quebra do sistema de proteção e consequente pirataria do software. 

Uma das maiores críticas a tecnologia tem se focado na perda de perfomance de jogos e no alto consumo de CPU. Reviewers e jornalistas apontaram queda de perfomance em comparação com jogos com Denuvo, enquanto a empresa declara em seu site oficial que seu software não impacta perfomance ou segurança de componentes das máquinas.
Além disso, a necessidade de conexão constante com a internet impede que jogadores possam usufruir do software de maneira offline ou que os mesmos possam emprestar suas cópias para colegas. Eventualmente, empresas costumam retirar a tecnologia algum tempo após lançamento ou após grupos de hackers conseguirem burlar o sistema, apesar de atualmente isso estar acontecendo com menor frequência. 

O mecanismo principal de funcionamento do Denuvo não é divulgado ao público, por razão de segurança da ferramenta. Sabe-se que o Denuvo atua em conjunto com outros mecanismos de proteção, como GDD/DRM do Steam da Valve, por exemplo. Apesar de seu mecanismo de ação não ser divulgado, a comunidade de crackers revelou que a ferramente funciona como uma caixa que armazena o conteúdo do jogo e se tranca em um ambiente virtual. A fechadura dessa caixa é encriptografada e a chave para essa fechadura é única para cada máquina, sendo assim cada chave é única e não poderia ser usada para destravar outros jogos em outras máquinas.
O Denuvo analisa componentes do hardware (HW ID) como parte do seu sistema antitampering, além da liçensa do software, ID de usuário (vínculado alguma conta, seja Steam, Origin, uPlay), chave de encriptação e alguns outros dados da máquina e usuário.

## Críticas
Uma das maiores críticas ao Denuvo é o impacto causado pelo software na perfomance dos jogos, impactando tanto nos loadings (em alguns casos, um aumento de 50% à 80%) e frame rate de algumas animações. 
Além disso, como uma DRM que funciona com a necessidade de acesso constante a internet, caso as empresas fechem seus servidores ou parem de dar suporte de alguma forma ao jogo, o usuário final pode perder acesso ao game, mesmo nos casos daqueles jogos single player, que não necessitariam de acesso a internet normalmente.
A Denuvo argumenta que o objetivo do software é garantir um período, normalmente nos primeiros meses de lançamento do jogo (a chamada janela de lançamento), de proteção contra pirataria, o que ajudaria nas vendas iniciais. Porém dado a desconfiança do público com as ferramentas de gestão de dados digitais pelos motivos citados, a notícia de que um jogo será lançado com Denuvo não costuma ser bem recebida. 

# Conclusão

Como foi discutido ao longo do artigo, ferramentas de DRM existem para proteger empresas contra a distribuição ilegal de cópias de seus produtos digitais. A pirataria é uma constante em todas as áreas das indústrias de produtos e entretenimento, seja cinema, moda, eletrônicos, música ou videogames (softwares). Dentro do meio digital, existem maneiras únicas de proteção que podem causar conflitos com compradores de cópias legais dos produtos. Pensando nisso, se faz necessário que as empresas busquem maneiras de proteger seus produtos que não afetem o consumidor final no futuro.

# Fontes

[Link 1](https://sci-hub.st/https://ieeexplore.ieee.org/abstract/document/9225560)
[Link 2](https://www.polygon.com/2017/10/12/16464616/middle-earth-shadow-of-war-drm-cracked-denuvo)
[Link 3](https://irdeto.com/denuvo/)
[Link 4](https://www.reddit.com/r/CrackStatus/comments/4k1qtg/here_is_some_real_information_about_how_denuvo/)
[Link 5](https://arstechnica.com/gaming/2018/12/evidence-continues-to-mount-about-how-bad-denuvo-is-for-pc-gaming-performance/)
[Link 6](https://sci-hub.st/https://ieeexplore.ieee.org/abstract/document/9225560)

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-0GsTofh)
# Projeto: Remake de site/app web

!(imagens/capa.png "Screenshot do projeto.")


Acesso: https://elc1090.github.io/project1-2025a-zerowin1/


#### Desenvolvedor(a)
Thales de Vargas Stamm - Sistemas de Informação

#### Cliente
Rafael Carneiro Pregardier

#### Site/app original
Steam

##### Link
https://store.steampowered.com/?l=portuguese

##### Descrição
A Steam é uma plataforma de distribuição digital de jogos que oferece uma ampla variedade de títulos e conteúdos relacionados. Ela permite aos usuários adquirir, baixar e atualizar jogos de forma integrada, gerenciando uma biblioteca pessoal com facilidade. O design é composto por cores mais escuras, mas com alguns "toques" mais chamativos. Seu layout é organizado e exibe uma variedade de itens: banners sazonais, carrosséis de jogos, seções de promoção, recomendações... Tudo de uma maneira dinâmica e interativa, com animações sutis que fazem com que o usuário continue engajado sem que se sinta sobrecarregado com a quantidade de informações na tela.

#### Demanda do(a) cliente
Poderia ter uma alteração estrutural em relação a posição dos jogos nas divisões. Além disso, número de jogos mostrados poderiam ser diminuídos. A implementação de um carrossel interativo com vários jogos a serem mostrado. Uma seção onde tem o trailer de algum jogo sendo reproduzido.

#### Desenvolvimento
Durante a reunião inicial com o cliente, definimos alguns pontos específicos sobre a direção do projeto. A principal demanda era oferecer uma interface limpa e intuitiva, o que levou a simplificar (ou remover) diversas seções presentes na Steam. Por exemplo, foi feita a remoção da barra lateral tradicional – considerada redundante – pois oferecia somente o acesso facilitado a recursos que podem ser acessados por meio de outras seções na página. Além disso, foi reduzido o número de jogos exibidos e o carrossel interativo também foi simplificado, exibindo apenas a capa do jogo. Detalhes como preço, categorias, comentários e outras informações só seriam apresentados após clique do usuário(feature não implementada).

Também foram eliminadas seções específicas, como “Por até R$ 20” e “Atualizações e ofertas”, para manter em tela específicamente o que o cliente "pediu" para ver. Em relação ao trailer dos jogos, enquanto na Steam é necessário acessar a página individual de um jogo para visualizar seu trailer, no remake foi proposta uma seção de “Destaques e Recomendados” onde, por padrão, o trailer de um jogo em destaque é reproduzido. Ao selecionar uma categoria(na seção de categorias), os jogos exibidos e o vídeo em reprodução se atualizariam de acordo com o filtro aplicado.

Todo o conteúdo visual foi coletado de fontes disponíveis na internet, normalmente inspecionando a página da Steam e salvando as imagens ou procurando alguma alternativa semelhante na internet. A única exceção foram as imagens das quatro categorias, que foram geradas por meio de uma ferramenta de IA.

#### Tecnologias
- HTML
- CSS
- JavaScript

#### Ambiente de desenvolvimento
VS Code

#### Referências e créditos
- https://getbootstrap.com/
- https://chatgpt.com/
- https://store.steampowered.com/?l=portuguese

- Usei o chatgpt para facilitar o preenchimento do código e pedir dicas de onde buscar conteúdo.
ex de prompt:
"de todos os itens presentes "loja, novidades, categorias" precisam de um dropdown, me ajude a selecionar 3 itens que são necessários para compor cada um"

- sobre a busca de conteúdo, foi mais para o carrossel interativo, inclusive encontrei modelos muito bons, mas como mantive no html/css básico, acabei optando por utilizar o do bootstrap.

- Em alteração e design dos elementos da tela (tamanhos, cores, posicionamento) consultei bastante o chat;

- Na primeira tentativa de colocar o vídeo para reproduzir, pensei em deixar ele mais "cinemático" e tirar botões da imagem (tela cheia, volume, pause da tela), assim controlando por eventos tipo onmouseover ou onclick, o chat também me ajudou com esses scripts mas no fim deixei somente o player.

---
Projeto entregue para a disciplina de [Desenvolvimento de Software para a Web](http://github.com/andreainfufsm/elc1090-2025a) em 2025a

<!-- Título -->
# Por Que Devo Preocupar Com Encapsulamento

***Conteúdo da Aula:***

Vamos a um exemplo clássico da literatura: o exemplo da conta-corrente.

Se nosso *software* é um *software* bancário, nós fatalmente teremos a classe `conta-corrente` em nossa aplicação.

Uma conta-corrente pode ter o nome do titular e o saldo da conta como atributos, além de ter os métodos sacar e depositar.

Nós enfrentamos um problema em nossa classe conta-corrente neste caso:

* Nós temos que ter uma maneira de não permitir que o nosso atributo saldo seja afetado por trocas de mensagens externas com outros objetos em nossa aplicação.

* Se nós não escondermos o atributo saldo da classe conta-corrente de ações externas, nós podemos ter um código errôneo em nossa aplicação que altera de maneira incorreta o saldo das contas-correntes gerenciadas pela aplicação que estamos escrevendo.

* Em nossa classe conta-corrente, a única maneira que podemos ter de alterar o atributo saldo é através de chamadas aos métodos sacar e depositar.

* Mas, nunca que o saldo poderia ser alterado de maneira direta, sem passar por estes métodos.

* Desta maneira, nós precisamos encapsular o atributo saldo da classe conta-corrente, prevenindo que o atributo seja acessado de maneira direta ou mesmo modificado de maneira direta.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-por-que-dev-pre-com-enc-enc-log-ori-obj-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-por-que-dev-pre-com-enc-enc-log-ori-obj-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-por-que-dev-pre-com-enc-enc-log-ori-obj-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-por-que-dev-pre-com-enc-enc-log-ori-obj-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-por-que-dev-pre-com-enc-enc-log-ori-obj-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-por-que-dev-pre-com-enc-enc-log-ori-obj-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")

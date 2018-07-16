# Tradução de Pokémon Black/White para Português Brasil

## Fluxo de tradução
Só deve ser traduzido um arquivo por vez para que cada commit identifique os status da tradução.

![Disponível](https://placehold.it/15/f03c15/000000?text=+) `Disponível` &rarr; ![Entregue](https://placehold.it/15/1589F0/000000?text=+) `Entregue` &rarr; ![Traduzido](https://placehold.it/15/c5f015/000000?text=+) `Traduzido`

Cada arquivo que está com o commit "Disponível" está pronto para tradução.

Após efetuar a tradução de um arquivo "Disponível", deve-se enviar as modificações com um commit "Entregue".

![Disponível](https://placehold.it/15/f03c15/000000?text=+) `Disponível` &rarr; ![Entregue](https://placehold.it/15/1589F0/000000?text=+) `Entregue`

Após a entrega de um arquivo, alguém irá revisar o arquivo e alterar o commit para "Traduzido".

![Entregue](https://placehold.it/15/1589F0/000000?text=+) `Entregue` &rarr; ![Traduzido](https://placehold.it/15/c5f015/000000?text=+) `Traduzido`.

Agora, só partir para o próximo arquivo :D

## Significado dos códigos nos arquivos

#### Quebras de linha
	\xfffe								- O texto seguinte é movido para uma nova linha.
	\xf000븅\x0001\x0001				  - O texto é mostrado em velocidade máxima.
	\xf000븁\x0000						- Aguarda até que o botão "A" seja pressionado. Se houver outra linha de texto logo depois, inicia outra caixa de diálogo.
	\xf000븀\x0000						- Aguarda até que o botão "A" seja pressionado. Se houver uma outra linha de texto logo depois, o texto seguinte será exibido em uma nova linha.

#### Alinhamento de Texto	(Linha por linha)
	<Blank>					 - Padrão, Alinhamento à esquerda
	\xf000봂\x0001\x0000		- Centro
	\xf000봃\x0001\x0000		- Alinhamento à direita

#### Cores
	\xf000봀\x0003\x000?\x000?\x0000	- Cor Superior/Sobreamento (os números ímpares são mais claros que os pares).
	\xf000봀\x0003\x0001\x0002\x0000	- Padrão
	\xf000봀\x0003\x0003\x0004\x0000	- Ciano
	\xf000봀\x0003\x0005\x0006\x0000	- Vermelho
	\xf000봀\x0003\x0007\x0008\x0000	- Preto

	\xf000\xff00\x0001\x000?			- Cor do Texto
	\xf000\xff00\x0001\x0000			- Preto
	\xf000\xff00\x0001\x0001			- Vermelho
	\xf000\xff00\x0001\x0002			- Azul
	\xf000\xff00\x0001\x0003			- Amarelo
	\xf000\xff00\x0001\x0004			- Verde

#### Outros
	\xf000븂\x0001\x0014	- Adiciona um pequena atraso.

	Desconhecido:
	\xf000븉\x0001\x000?	- Visto durante as conversas com N, usado apenas para as mensagens dele.
	\xf000븉\x0001\x0000
	\xf000븉\x0001\x0001

## Descrição de cada arquivo
Como a lista de arquivo é muito grande, todas a descrição está sendo colocada em uma página separada. Segue o link para a página.
[Descrição dos arquivos](descricao_dos_arquivos.md)

## Links úteis
- Projeto de tradução para o inglês iniciado no fórum Projectpokemon.
[https://projectpokemon.org/home/forums/topic/10419-pokemon-black-and-white-translation-project/](https://projectpokemon.org/home/forums/topic/10419-pokemon-black-and-white-translation-project/)
- Projeto de tradução para o português iniciado no fórum Projectpokemon.
[https://projectpokemon.org/home/forums/topic/10518-pokemon-black-white-portuguese-translation/](https://projectpokemon.org/home/forums/topic/10518-pokemon-black-white-portuguese-translation/)

## Outras informações
Confira as ferramentas de Romhacking para Pokémon Black/White no seguinte repositório.
https://github.com/vagnerlandio/Pokemon-Black-White-Romhacking-Tools

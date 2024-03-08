# Game Super Mario

🇧🇷

## Tecnologias Usadas
HTML, CSS, e JavaScript.

## Como visualizar o projeto?
Disponível do link https://github.com/Paulosxb/Game-do-Coelho/


##


## Como funciona o projeto?
Game simples utilizando DOM para fazer a manipulação do HTML para criar interatividade.

### DOM - Manipulação do HTML alterando classes:
Inicialmente as imagens foram inseridas separadas das classes onde contém as animações.

Onde as animações foram criadas dentro do CSS em classes distintas.

#

Sendo inserido no JavaScript a função onde irá unir as duas classes no HTML criando o efeito visual do salto. Sendo utilizado a função setTimeOut para que após o determinado tempo que dura a animação de salto, seja excluido do html a classe Jump, finalizando assim a animação.

#

Após a função ser ativada o HTML terá o seguinte comportamento a baixo. Onde a classe Jump é removida pelo JavaScript após o tempo configurado que durará a animação do salto.

#

A Função Start será iniciada com o pressionamento de alguma tecla do teclado, onde irá substituir a imagem do Mario para um gif com o mesmo correndo, e iniciar as animações e som de fundo. 

#

Foi utilizada a função .offsetLeft para monitoramento da posição das imagens, desta forma foi possivel criar regras para que o JavaScript entenda quando a imagem do Mario está sobre a imagem da tubução, assim parando as animações quando todas as condições do IF forem verdadeiras.

# Lógica utilizada na animação do piso

Foram adicionadas 3 imagens, ao iniciar o game o javaScript iniciará a animação das imagens, no CSS está configurada um tempo para que a primeira e segunda imagem iniciem juntas, quando o canto superior direito da segunda imagem chegar ao final da tela, a primeira imagem ficará abaixo das demais sem animação e a animação da terceira imagem será iniciada, ficando assim em loop com a segunda imagem até o game-over.










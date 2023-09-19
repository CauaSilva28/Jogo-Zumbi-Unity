# Jogo Unity
<p>Feito por Cauã Silva👦 e Juliana Dantas👩</p>
<p>2°Jogos Digitais🕹️</p>

## Link do jogo no drive
https://drive.google.com/file/d/1jKhN5846LeQuEzGEf-Vc_4EgAPwARCT6/view?usp=sharing

## Vídeos mostrando o jogo
https://drive.google.com/file/d/1lr_Fz5KNc5L4wxyFL2Ih5-ScuXMqzLMY/view?usp=sharing

## Explicação 1°Fase
<p>O jogador deve controlar o personagem (Michael) e derrotar os zumbis que vao surgindo sem deixá-los atravessar o limite. A cena muda após 1 minuto.</p>

## Explicação 2°Fase
<p>O jogador continua matando zumbis sem deixá-los atravessar o limite, porém, agora possui um boss com muita vida que ele precisa derrotar para vencer.</p>

<img src='img/controles.jpg' />

## Explicação projeto
<img src='img/cenas.jpg' />
<p>O jogo possui 3 cenas, mas apenas 2 delas é o jogo, a outra é de fim do jogo.</p>

<p>Ao clicar em iniciar, a primeira cena "Fase1" se inicia.</p>
<p>Após completar um minuto matando os zumbis, a segunda cena se inicia "Fase2".</p>
<p>Se algum zumbi atravessou o limite, irá aparecer a cena com a tela de fim de jogo.</p>
<p>Se o jogador conseguir matar o boss, irá aparecer a cena com a tela de fim de jogo.</p>

## Personagem
<p>O personagem possui os scripts de movimento, arma e mudar cena.</p>
<p>O script de movimento irá movimentar o personagem no eixo Z, com o W e o S.</p>
<p>O script de arma é o que faz atirar, nele possui objetos como cano da arma e bala. O cano da arma é o responsável por ejetar varias balas que foram feitas utilizando sphere. Já a bala é composta por um script que faz o seu movimento, sua velocidade e um código para destrui-lá ao encostar nas bordas do cenário, pois as sphere vão sendo criadas a cada click do jogador e vai ter uma hora que vai ter tantas sphere que é capaz do jogo crashar. Além de ser responsável por destruir/matar os zumbis e o boss.</p>
<img src='img/scriptbala.jpg' />

## Zumbis
<img src='img/zumbi.jpg' />
<p>O zumbi foi pego no Assets e ja veio com algumas animações e scripts. Nele adicionamos um script para movimentá-lo sozinho e fazer spawnar varios deles em lugares aleatórios em uma área do cenário. O zumbi também possui vidas, que são perdidas ao colidir com a "bala". Se ele colidir com o gameObject vazio que fica atrás do personagem, a cena é mudada para a área de derrota.</p>
<img src='img/scriptzumbi.jpg' />

## Boss
<img src='img/boss.jpg' />
<p>O boss possui os mesmos códigos de movimento dos zumbis, o que muda é a sua velocidade e que ele possui mais vida. Se o boss perder todas as suas vidas, a cena é mudada para a área de vitória.</p>
<img src='img/scriptboss.jpg' />

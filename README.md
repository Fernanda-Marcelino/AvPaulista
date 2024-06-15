# Avenida Paulista

## Dupla: Carlos Alarcon e Fernanda Viana
Atividade do projeto de São Paulo, fase avenida Paulista.

## Link do projeto no Drive
https://drive.google.com/file/d/1x1NvELIOoOHAzldx_LJjKMo654Q_4MCf/view?usp=drivesdk

## Sobre nossa fase:
Nessa fase o personagem terá como objetivo fazer grafites nos prédios da Avenida Paulista enquanto é perseguido por um policial e desviar dos carros que estão passando pela avenida, e para passar de fase o jogador deverá concluir as 15 pichações propostas na fase.

## Construção do cenário
Para o cenário desta fase utilizamos alguns assets da Store e Prefabs, como os prédios, calçadas, a rua e os carros. Tambem utilizamos um Sky Box para o céu. Pintamos alguns planos para fazer a ciclovia central e planos menores para fazer as linhas amarelas da ciclovia.

## Policial
O policial será uma aranha-fio-de-ouro (um dos animais propostos para o projeto). Usamos um som de algema quando o policial alcançar o personagem, para mostrar que ele foi preso. "Explicar o código de perseguir e prender o personagem!"

## Personagem
Como os animais do projeto serão nossos personagens, fizemos o jogo em terceira pessoa para mostrar os animais. O personagem dessa fase será o Saruê e ele terá uma lata de tinta na mão para poder fazer os grafites nos prédios. Ele possui um script simples para movimentação e rotação.

## Códigos

## Movimento do carro
![image](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/096f7b2b-f795-4f22-bdcf-1ade536a90a1)

Este código faz com que o carro se mova no eixo Z (para frente), e o destrói quando ele se move para além de uma certa posição do eixo X, que é aonde acaba a cena.


## Policial
![! image (httpsgithub comFernanda-MarcelinoAvPaulistaassets128370700b8e9a2e9-c735-4c85-ba53-7f77d21df0e9) ! image (httpsgithub comFernanda-MarcelinoAvPaulistaassets128370700a14d188f-3f2b-4056-997d-](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/40810452-1450-4925-b76a-75450a76d26a)

Esse código faz com que o policial siga o personagem usando o sistema de navegação NavMeshAgent.


## Personagem
![Design sem nome](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/7c3087c0-9479-44e6-8de1-c2accdcc0769)

O código acima controla o personagem e támbem utiliza algumas interações, como a detecção de colisões com os carros e a possibilidade de ser preso pelo policial.


## Pichar
![Design sem nome (1)](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/bbcc801f-7c6c-414a-8d83-f8c6aa30e5a9)

Este código permite que jogador realize pichações em prédios. Ele usa Raycasting para detectar onde o jogador está apontando na tela e se apontar para um prédio, permite que o jogador faça uma pichação. O número de pichações é contado e exibido na tela. Quando o jogador completa 15 pichações, a cena "telaGanhou" é carregada.


## Rotação da câmera
![image](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/dc6704dd-52f8-47aa-8733-66f4123d81ec)

O código controla a rotação da câmera verticalmente com base no movimento do mouse.


## Spawnar carros
![image](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/c993cb01-c875-44b9-a236-ee56524d8224)

Esse código cria carros em pontos de spawn especificados repetidamente ao longo do tempo.

## Voltar fase
![image](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/4409c057-873e-45cc-adcb-b80230467daa)

Usamos esse código para mudar uma cena, ele foi anexado a um botão que, quando clicado, retorna o jogador a cena principal.


## Voltar Scroll
![image](https://github.com/Fernanda-Marcelino/AvPaulista/assets/128370700/ba521656-351c-4afa-93c8-0f083e1fd070)

Este código é responsável por fazer reaparecer o scroll do mouse na tela.





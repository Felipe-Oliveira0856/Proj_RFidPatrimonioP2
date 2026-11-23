# Projeto Avaliativo 2 - Internet das Coisas

#### Projeto avaliativo prático para as aulas do Professor Lúcio, utilizando IoT como ESP32, RFid e etc. juntamente com uma interface web.

#### Link: https://canva.link/0fs2292a9hfqszx

#

### - Tema

#### A Estrutura do Projeto tem como objetivo realizar o desenvolvimento para o controle de patrimônio, no qual terá o uso das tecnologias ESP32 e RFID.

#

### - Cenário

#### Para o cenário pensado desse projeto, vamos imaginar uma escola, na qual uma das salas tem exatamente um certo número fixo de carteiras e cadeiras. 
#### Porém, um dia, por causa de aulas dinâmicas ou falta de espaço ou outro motivo, uma turma pega algum desses móveis emprestados para outra sala e esquecem de devolver. 
#### Isso pode gerar uma dor de cabeça para quem é responsável de manter organização, e até para a sala, pela falta de espaço para os alunos.

#

### - Proposta

#### Para resolver esse problema, foi pensado em um sistema IoT usando ESP32 e RFID para identificar onde estão esses móveis. Cada carteira e cadeira receberia uma etiqueta RFID com um código único, e estaria posicionado debaixo de cada móvel.

#

### - Identificação do RFID

#### Para a posição do leitor, foi pensado em coloca-los diretamente nas portas de cada sala de aula. Caso o móvel passe pelo leitor da sala correta onde ele pertence, será registrado como positivo no sistema. 
#### Entretanto, no cenário em que o móvel entra em uma sala diferente, o leitor registrará a entrada com indicação de que o móvel não é presente na sala em questão.

#

### - Componentes Utilizados:
#### 1x ESP32 DevKit v1
#### 1x MFRC522 - Leitor RFID
#### 1x Protoboard
#### 2x Resistores
#### 11x Jumpers
#### 2x LEDs (Verde e Vermelha)

#

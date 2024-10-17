### Parte 1: Blink Led Interno  

Instale a Arduino IDE em seu computador e assista aos vídeos indicados nos autoestudos conforme o roteiro descrito anteriormente. Você deverá realizar o "blink" com esse LED Interno e postar em seu GitHub as evidências dessa realização. 

Você vai fazer o led ficar aceso por um tempo X, apagar e aguardar Y segundos e depois voltar a acender, propondo um loop que gera uma "luz piscando".


[Codigo](./Blink/Blink.ino)

[Print do Codigo](./printIDE.png)

[Video de demonstração](./IMG_8770.MOV)

### Parte 2: Simulando Blink Externo

Na imagem anterior do Arduino UNO, os quadradinhos pretos numerados (A0, A1, A2, ..., ~11, 12, 13) são as portas de entrada e/ou saídas para os nossos componentes. Podemos dizer, por exemplo, que um LED está na "porta 6" e que outro está na "porta 13". Nós vamos escrever programas que recebem ou enviam comandos específicos para esses "endereços", por exemplo, definimos o pino 13 como uma saída `pinMode(13, OUTPUT);` e depois enviamos o comando para "ligar o led" `digitalWrite(13, HIGH);`

Nessa `parte 2` você deverá fazer uma simulação **no TinkerCad** com uma montagem do pisca-pisca com Arduino Uno. Ao clicar no play do TinkerCad, o projeto deve executar sem erros uma rotina que simula um pisca-pisca de qualquer cadência. Utilize no projeto um protoboard, ligações elétricas, LED (precisa ser um OFF_BOARD), resistor e um Arduino. 

Envie o link do seu projeto do Tinkercad na Adalove. Obtenha o código do Tinkercad, publique no seu repositório pessoal do GitHub e também envie este link no card.

Link do tinkercad: _https://www.tinkercad.com/things/ktXFDhI3okb/editel?sharecode=nJMEeix6-D5Pl6L8UjwUngfcFcJIc0f6NSztn2oF9Ww_

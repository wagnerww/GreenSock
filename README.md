# GreenSock

## Basics:

### `.set()`

- O set é disparado quando a página é rendererizada, ou seja, o "start". Então tudo vai aparecer já pronto para o usuário. Pode ser usado para esconder algo, ou "bagunçar" para depois reorganizar. Esse método não anima nada.

### `.to()`

- O to é um método disparado após um time de renderização. Por exemplo, executar após 3 segundos depois de carregados ou depois de invocar uma função, etc.

### `.from()`

- O from é o inicio da animação, ou seja, ele anima quando a página é rendererizada até o stado original dele.

### `.fromTo()`

- Junta os 2 métodos from e to, comecando e indo para um determinado ponto

### `delay`

- Vai esperar um certo tempo para executar o metodo

### `ease`

- O ease faz com que temos uma animação masi controlada, lenta-rapida-lenta, balalanceada, etc. Modelos: https://greensock.com/ease-visualizer

### `.staggeFrom()`

- O staggerFrom só fuiona com listas, um único item ele não fuciona legal. Depois que ele termina 1 item, ele passa para animar o outro após um determinado tempo

### `.staggeTo()`

- O staggerTo só fuiona com listas, um único item ele não fuciona legal. Depois que ele termina 1 item, ele passa para animar o outro após um determinado tempo

### `.staggerFromTo()`

- O staggerFromTo só fuiona com listas, um único item ele não fuciona legal. Depois que ele termina 1 item, ele passa para animar o outro após um determinado tempo do incio para um final

### `Cycle`

- A propriedade de Cycle só funciona com o método stagger. É possível brincar com a lista dos objetos, passando função, ou formatando um elemento de uma forma e outro de outra.

### `loop`

- repeat com valores positivos, irão significar o número de vezes que a animação deve repetir. -1 informa que é infinito. Para deixar a animação mais fluida, aplicar o yoyo:true

### `Callback`

- Pré determina a execução das funções nos momentos:OnStart, onUpdate, onComplete, onRepeat

## Time-Line:

### `Encadeamento`

- Utilizar o método TimelineMax(), e chamar uma função/método de forma "corrida"um atrás do outro.

### `Position-parameter`

- É uma forma de aplicar delay na time-line(positive-relative(+=1)) ou overlap(negative-relative/passar pos cima ou acontecer(-=1)) junto)

### `Control`

- É uma maneira de controlar o inicio da animação, pausar, etc. Como se fosse um player

### `Scale`

- Controle da velocidade da animação parametrizada

# LINKS e URLS  

## Url básica

Para anexar uma url em forma de link basta colocar o seu endereço entre os sinais de maior que ```>``` e menor que ```<```, por exemplo:  
<https://github.com/>  

    <https://github.com/>

## Links 

Para criar um [link](https://github.com/), precisa-se colocar o texto entre colchetes e logo em seguida a URL entre parênteses  
  
    Para criar um [link](https://github.com/), precisa-se colocar o texto entre [...]

Pode-se colocar um título nos links, títulos aparecem como um auxiliar quando se passa o mouse por cima do [link](https://github.com/, "isto é um título").

    [...] passa o mouse por cima do [link](https://github.com/, "isto é um título").

> Vale ressaltar que todo e qualquer link deve estar em uma linha só.

## Links referenciados  

### Primeira parte 

Links referenciados são um estilo diferente de anexar links, eles são mais fáceis de ler e mais rápidos, além de que podem ser [usados][1] em diversas [palavras][1] de uma vez só.  
  
Para construir estes [links][1] coloca-se o texto entre o par de colchetes e logo em seguida um outro par de colchetes com uma referência que aponta pro url e título do link, assim:

    Para construir estes [links][1] coloca-se o texto [...]
    além de que podem ser [usados][1] [...]
    em diversas [palavras][1] de uma vez só.  
  

### Segunda Parte

Usando como exemplo o texto do subtópico anterior, podemos colocar a referência no final do documento. Uma sintaxe possível é a seguinte:

    [1]: <https://github.com/>

> Cada sintaxe tem seus nuances, mas todos devem começar com o texto de referência entre colchetes seguido de dois pontos e um espaço

A seguir, uma lista de formatos possíveis de referenciar:

- ```[1]: https://github.com/```
- ```[1]: https://github.com/ "isto é um título"```
- ```[1]: https://github.com/ 'isto é um título'```
- ```[1]: https://github.com/ (isto é um título)```
- ```[1]: <https://github.com/> "isto é um título"```
- ```[1]: <https://github.com/> 'isto é um título'```
- ```[1]: <https://github.com/> (isto é um título)```

## Imagens  

Imagens seguem a mesma sintaxe de um link, a única diferença é que devem ser iniciados com um de exclamação ```!```.  

![uma paisagem qualquer](https://cursinhoparamedicina.com.br/wp-content/uploads/2022/10/Paisagem-1.jpg)

> ```![uma paisagem qualquer](https://cursinhoparamedicina.com.br/wp-content/uploads/2022/10/Paisagem-1.jpg)```

### Adiocionando links em uma imagem  

Pode-se imbuir um link em uma imagem usando a' seguinte sintaxe:

[![Clique em mim!](https://planetacampo.canalrural.com.br/wp-content/uploads/2023/08/ChatGPT.jpg)](https://chatgpt.com/)
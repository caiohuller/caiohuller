Código escolhido: Alaragamento de contraste.

Explicação técnica: O contraste serve para melhorar a qualidade da imagem,que ocorre por uma transferência radiométrica em cada "pixel", com o objetivo de aumentar a discriminação visual entre os objetos presentes na imagem. O contraste pode ser definido como a razão entre os seus níveis de cinza médios. 

Como ele está emplementado: É feito por meio de uma estrutura de repetição (for) uma verificação com uma estrutura condicioal (if and else), dentro da matriz da imagem, a fim de saber a quatidade de cinza médios e então fazer as operações:
Se o nivel de cinza médio for menor ou igual a 85, é dividido pela metade;
se o nivel de cinza médio for maior que 85 e menor que 170, mmultiplicasse o valor por 2 e subtrai 127;
E se o nivel de cinza médio for maior ou igual a 170, dividisse pela metade e soma 128.

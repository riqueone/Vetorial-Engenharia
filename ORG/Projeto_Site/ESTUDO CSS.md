
## ANOTAÇÃO 1 - PSICOLOGIA DAS CORES
[VÍDEO](https://www.youtube.com/watch?v=A8UNBs7nxw4&list=PLHz_AreHm4dlUpEXkY1AyVLQGcpSgVF8s&index=2)
![[Pasted image 20260828155040.png]]

## ANOTAÇÃO 2 - CÍRCULO CROMÁTICO
[VÍDEO](https://www.youtube.com/watch?v=E2gaDa4ZaTc&list=PLHz_AreHm4dlUpEXkY1AyVLQGcpSgVF8s&index=4)
![[Pasted image 20260828164000.png]]

## ANOTAÇÃO 3 - CRIAÇÃO DAS PALETAS
[ADOBE COLOR](https://color.adobe.com/create/color-wheel)
[PALETTON](https://paletton.com/)

## ANOTAÇÃO 4 - IMPORTAÇÃO DE FONTES
[GOOGLE FONTES](https://fonts.google.com/)

## ANOTAÇÃO 5 - PSUDOCLASSES
[VÍDEO](https://www.youtube.com/watch?v=WPtRX4n0UJs&list=PLHz_AreHm4dlUpEXkY1AyVLQGcpSgVF8s&index=21)

h1#topico{
*Vai alterar apenas os h1 que tenham o ID "topico"*
}

\#tópico{
*Vai alterar todas as tags que tenham o ID "topico"*
}

No CSS quando eu colocar dois pontos ( : ) depois de um elemento seja ela um ID, uma CLASSE ou uma TAG mesmo, que eu vou revelar suas pseudoclasses, que é como se fosse suas propriedades

EX: div:hover {
*Quando alguma div estiver em foco do mouse vai acontecer algo*
}

Outra coisa interessante é o sinal de *Child* representado pelo ">", em outras palavras, as divs que contenham um "filho" p serão desencadeadas quando passar o mouse em cima do div

div:hover > p {

}

## ANOTAÇÃO 6 - TIPOS DE CAIXAS (BOXS)
[VÍDEO](https://www.youtube.com/watch?v=3ZFYXkzXhqE&list=PLHz_AreHm4dlUpEXkY1AyVLQGcpSgVF8s&index=23)

![[Pasted image 20260830115128.png]]

Os "box-levels" são tags que se separam quebrando a linha e naturalmente ocupa a linha inteira, ou seja, quando eu coloco uma após a outra elas serão desenhadas em linhas diferentes, enquanto o "inline-level" desenha na mesma linha.

Quando eu definir "display:block" eu estou tornando esses elemento um BOX-LEVEL

>[!tip] margin: auto
>Centraliza horizontalmente uma Box, por incrível que parece.
>
## ANOTAÇÃO 7 - GROUNPING TAGS
[VÍDEO](https://www.youtube.com/watch?v=JPMm-jyKOaM&list=PLHz_AreHm4dlUpEXkY1AyVLQGcpSgVF8s&index=26&pp=iAQB)

São tags que na prática são semelhantes as **\<divs>**, porém é importante usar as grouping tags pois elas ajudam a organizar a estrutura do site, e também a indexação por serviços de busca
EX:
\<header>
\<main>
\<footer>

dentre outras

## ANOTAÇÃO 8 - RESPONSIVIDADE DE TAMANHO PARA IMAGENS
[VÍDEO](https://www.youtube.com/watch?v=rAdHLNBTCgs&list=PLHz_AreHm4dlUpEXkY1AyVLQGcpSgVF8s&index=38)

Existem várias formas de fazer isso, uma bem simples e que funciona bem é a união de duas técnicas, a primeira é definir tamanhos responsivos para as tags pai.
*min-width:*
*max-width:* 
Quando a tela for maior que o tamanho máximo ele NÃO permite que a tag cresça mais, o mesmo acontece quando a tela fica menor que o tamanho mínimo, ele não permite que nenhum elemento transborde.
E para completar, nas propriedades da imagem vamos colocar *width:100%* pois ele vai acompanhar a responsividade do pai.

Para imagens existe uma tag muito boa que é a **\<picture>** dentro dela podemos configurar propriedades que quando uma imagem reduza muito de tamanho (e por consequência fique difícil de reconhecer) podemos substituí-la por outra com um recorte melhor


# info-about-js-start-
# Js what is this? 
*js это язык программирования, которая на данный момент очень популярна в мире, возможно самая популярная.
Сам язык появился в 1995 году благодаря Brendan Eich.
Сам язык после выпуска работал всего 10 дней, его называли Mocha,
но спустя время его назвали LiveScript что означает оживлять.
После его переименовали в javascript потому что на тот момент язык Java был популярен, таким хитрым ходом об этом языке начали узнаввать.
Ecmascript это стандартный Js:*
*  *во первых был создан, чтобы избежать багов или различных сбоев придумали ecma.* 
*  *во вторых основная задача этой системы в том,чтобы один синтаксис был в любом проекте, программы написанном на джава скрипте.*
  



  *Самая популярная версия ecma6 , которая была в 2015 году и с каждым годом она обновляется, выпускается сначала ecma , а потом уже и новая версия джавы.*

  *Сам язык является динамическим и интерактивным. Интерактивным делаем его мы, люди.
  Динамическим делает его отсутсвие типизации, то есть типизация зависит от значения, не от variable.*
  

  *Есть три способа увидеть результат в скрипте:*
  1. *при помощи браузера*
  2. *при расширении code runner*
  3. *при помощи node js , если мы ее пропишем в консоли*


## Синтаксис JS
В скрипте 3 variable :
1. var, очень схожи с let  только var cтарый
2. let позволяет писать нам любой тип значения, то есть если мы в с++ использовали определенные типы для цифр текста, то тут нет, тут все зависит от значения.
3. const это уникальный variable который не изменяется, у него также все зависит от значения, но в дальнейшем мы не можем изменить его, к примеру в let and var мы могли записать цифру и позже изменить его, то есть написать в дальнейшем не цифру, а текст, с const у нас нету такой возможности.

Значения также делятся на два типа Primitive and object:
1. primitive: number, string, boolean, undefined, null, symbol,bigint.
2. object: function, array and more.

То есть 7 примитивных и 1 обьект. 
Примитивные могут вместить в себя только одно значение , в то время как обьект вмешают в себя более 1 и дальше.

console.log позволяет нам выводить все , то есть выполняет функцию вывода на экран .

## Сonditions, loop,  functions 

Condition in js we can write in 3 forms:
1. if, else if and if
2. switch case
3. ternary operator for easy logic

loop we also can write in 3 forms :
1.  with for
2.  with while
3.  with do while but not mush people use this metod
 
 Все они работают одинаково, но только порядок написания разный.

 Также с функциями, они также делятся на три вида:
 1. Declaration
 2. expression (anonymious, arrow)
 3. IIFE не испозьзуют, но знать надо
 

 На мой вхгляд самые удобные Expression(arrow) and Declaration.
 Они также выполняют одинаковую функцию, но структура написания отличаетсяю.

 Пример Declaration and loop (for):
 ```js
 function generateMultiplicationTable(num)
{
    let result = ' '
    for(let i=1; i<=10; i++)
    {
     result += (num + " X " + i + " = " + (num * i) +("\n"));    
    }
    return result
}
console.log(generateMultiplicationTable(5));
```
 Примеры Expression (arrow) and ternary operator:
 ```js
 let endLine= (num)=>{
   let result= num%10==9 ? true : false;
   return result;
}
console.log(endLine(149));
console.log(endLine(387));
console.log(endLine(29));
```
 ```js
let checkNumber =(num) => {
   return num > 0 ? "positive": num < 0 ? "negative" : "zero";
}
console.log(checkNumber(5));
console.log(checkNumber(-8));
console.log(checkNumber(0));
```
   
## ***Spasibo za Vnimanie!!***

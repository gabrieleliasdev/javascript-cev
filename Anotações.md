> Client x Server

Há tecnologia para Cliente e para Servidor

O JavaScript surgiu como uma tecnologia para clientes.

Tecnologias relacionadas: Website
HTML » Conteúdo
CSS » Designer/Estilo
JS » Programador/Interação


- Basic Timeline -
» 1970 » DARPA » Arpanet » Internet
» 1993 » HTML » Protocolo http » Juntou-se ao TCPIP » World Wide Web (www) » CERN » Mosaic
» 1994 » Netscape
» 1995 » Moca » Java » JavaScript (Moca) » Microsoft » Internt Explores
» 1997 » ECMA » Padronização do Linguagem (ISO Europeia)
» 2002 » Netscape Vs Microsoft » Mozilla » Firefox
» 2008 » Google Chrome
» 2009 » V8 Google Chrome (Open Source)
» 2010 » node.js (roda JavaScript sem navegador)

ECAMScripit » Versão Padronizada do JavaScript » 1997 v1.0 » 1998 v2.0
» 1999 v3.0 | Compatibilidade com Expressões Regulares, Bloco Try Cath p/tratativa de erros)
» 2009 v.ES5 | Mais Popular de todas, compatível com quase todos os navegadores e com JSON.
» 2015 v.ES6 | Declardores left e cont e as strings e templates
» 2016 v.ES2016 | Operador de Exponencialização
» 2017 v.ES2017 | Compatibilidade com Funções Assíncronas
» 2018 v.ES2018 | Novidades em expressões regulares e as Promessas/Promise

Referência do JavaScript

https://developer.mozilla.org/pt-BR/

https://www.ecma-international.org/ » Standard ECMA-262

Aprende lógica de programação, programando em JavaScript

Há 03 formas de delimitar uma strings dentro do JS
"" / '' / ``

Regras de Identificadores

1ª Podem começar com lentra, $ ou _
2ª Não podem começar com números
3ª É possível usar letras ou números
4ª É possívelusar acentos e simbolos
5ª Não podem conter espaços
6ª Não podem ser palavras reservadas

Dicas para nome de Identificadores

1ª Maiúsculas e minúsculas fazem diferença
2ª Tente escolher nomes coerentes para as variáveis
3ª Evite se tornar um 'programador alfabeto' ou um 'programador contador'

Data Types » typeof
» number (Infinity | NaN)
» string
» boolean
» null
» undefined
» object (Array)
» function

Abrindo novo terminal Ctr + Shift + Crase
Ctrl + L

var ~ let ~ const

Comentários
CSS » /* */
HTML » <!-- -->
JS » //

alert('') » Janela de Alerta (window.)   
confirm('') » Janela de Confirmação
prompt('') » Janela de Interação/Input

Operador Soma
( + ) tem o significado de concatenação e de soma
(string + string) para concatenação
(number + number) para adição

prompt sempre receberá uma string, é necessário realizar uma conversão.

String » Número
- Number.parseInt(n)
- Number.parse Float(n)
- Number (n) | O JS definirá.

Número » String»
- String(n)
- n.toString()

//Formantando strings
var s = 'JavaScript'
'Eu estou aprendendo s' //não faz interpolação
'Eu estou aprendendo' + s //usa concatenação
`Eu estou aprendendo ${s}` //usa template string

Atributos
s.length //quantos caracteres a string tem
s.toUpperCase() // tudo para 'MAIÚSCULAS'
S.tolLowerCase() // tudu para 'minúsculas'

Comando
document.write() //escreve na tela
document.writeln() //escreve na tela e quebra linha
<br/> //quebra linha

//Formatando Números
var n1 = 1543.5
n1.toFixed(2) //02 casas decimais
n1.toFixed(2).replace('.', ',')
n1.toLocaleString('pt-BR'), {style: 'currency', currency: 'BRL'}) //string localizada NO MUNDO EM OBJETO

//Operadores
» aritméticos ( + | - | * | / | % | ** ) » Operadores Binários
» atribuição
Ordem de Procedência
- var a = 5 + 3 = 8
- var b = a % 5 = 3
- var c = 5 * b ** 2 = 45
- var d = 10 - a / 2 = 6
- var e = 6 * 2 / d = 2
- var f = b % e + 4 / e = 3
Simplificando
- n = n + 4 | n += 4 | n++ ou ++n (pré e pós incremento)
» Relacionais ( > | < | >= | <= | == | != )
- Identidade ( === )
» Lógicos
- ! = negação | Operador Unário ( true or false )
- && = conjução | Operador Binário (só satisfaz se as 02 forem verdadeiras)
- || = disjunção | Operador Binário (basta que apenas um seja verdadeiro)
Ordem de Precedências
1ª Operadores Aritméricos
2ª Operadores Relacionais
3ª Operadores Lógicos 
» Ternário ( ? | : )
» typeof (tipo de operador)
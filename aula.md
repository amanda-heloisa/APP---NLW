## Linguagem de programação

Maneira de dar instrução ao computador.
Como um lego, você irá utilizar peças para criar algoritmos, ou seja, para resolver problemas.

> 💡 **Algoritmo**: Sequência de passos lógica e finita para resolução de um problema.

## Peças de uma linguagem

- Comentários
- Declaração de variáveis (const, let)
- Operadores (atribuição, concatenação, matemáticos, lógicos )
- Tipos de dados (string, number, boolean)
- Estrutura de dados (functions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for, while)

# Fases da resolução de um problema

Coletar os dados
Processar os dados (manipular, alterar ...)
Apresentar os dados

## Escopo e variáveis:

- [x] Variáveis globais e locais
- [x] Constantes

## Tipos de dados:

- [x] Strings (texto): "" '' ``
- [x] Numbers: 2 1.4
- [x] Boolean: true, false

# Operadores


- [x] Operadores de atribuição de valor: =
- [x] Operador de contatenação: +
- [x] Operadores de comparação: 
    * ==(igual) 
    * !=(diferente)
    * < menor > maior
    * <= menor igual >= maior igual
-[x] Spread operator: ...

## Estruturas de dados:

### Arrays: 

- [x] Uma lista que contém qualquer tipo de dado 
- [x] Métodos de array: push, [find, forEch, filter, map] : HOF (Higher order functions) 

### Objetos:

- [x] Atributos e métodos
- [x] Criação e manipulação de objetos
- [x] Acesso a propriedades de objetos

### Functions

- [x] criar, passar argumento
- [x] excutar
- [x] arrow function / named function

# Estrutura de reptição
- [x] while

# Condicionais 
- [x] switch
- [x] if/else/*

## Módulos em Node.js:
- [x] Importação de módulos (require, CommonJS)
- [x] Biblioteca 'inquirer' para criar prompts interativos
- [x] Módulo fs (file system)

## JSON

- [x] Javascript Object Notation (.json)
- [x] JSON.parse() : Transforma de JSON para JS
- [x] JSON.stringfy() : Transforma de JS para JSON

## Programação assíncrona e Promises:

- [x] Uso de funções assíncronas (async/await)

# Anotações
- Atenção na digitação, cada letra importa, e letras erradas causam erros de código;
- let: muda;
- const: não muda seu valor e consequentemente e dá erro de código;
- Dentro da chave: variável local;
- Fora da chave: variável global;
- .(pontinho) para acessar algo, uma propriedade;

# Teste de código
## 01: 
// Hello world - Olá, Mundo!
const mensagem = "olá eu"

{
    const mensagem = "olá, mundo!" 
    console.log(mensagem);
}
console.log(mensagem);

## 02:
// arrays, objetos
let metas = ["amanda", "alô"]
console.log(metas[1] + ", " + metas[0])

let meta = {
    value: 'ler um livro por mês',
    address: 2,
    checked: false,
    log: (info) => {
        console.log(info)
    }
}

meta.value = "não é mais ler um livro"
meta.log(meta.value)

## 03:
//function // arrow function (arrow = Seta)
const criarMeta = () => {}

function criarMeta() {}
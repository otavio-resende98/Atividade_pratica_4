# Atividade_pratica_4

<p>Diferenças entre as linguagens TypeScript e Javascript</p>

<img src="https://svitla.com/uploads_converted/2/13982-javascript_vs_typescript.webp?1664279370" alt="TypeScript x JavaScript">

## Links para documentação de ambas as linguagens
  - [Documentação do JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
  - [Documentação TypeScript](https://www.typescriptlang.org/pt/docs/)


## Perguntas frequentes realizadas sobre TypeScript, suas diferenças e vantagens/desvantagens em relação ao JavaScript

  - **O que é TypeScript?**
		*TypeScript é uma linguagem de programação e também um superconjunto de JavaScript. Isso quer dizer que todo o código JavaScript é perfeitamente aceito em um programa de JavaScript, adicionando uma série de recursos a mais, em especial relacionados a tipagem.*

  - **Quais são as vantagens do TypeScript?**
		*São diversas as vantagens, em especial ligadas a tipagem estática:*
		1. *Feedback mais rápido de erros e em tempo de compilação;*
		2. *Processo de refatoração mais fácil;*
		3. *Autocomplete da linguagem;*
		4. *Possibilidade de migrar de linguagem de pouco a pouco;*
		5. *Ter uma empresa grande por trás para trazer agilidade nas novas versões, no caso a Microsoft;*

	- **Qual é a diferença entre JavaScript e TypeScript?**
		*São duas linguagens de programação diferentes, porém uma é o superconjunto de outra. TypeScript é esse superconjunto, possibilitando que você use absolutamente tudo do JavaScript de forma válida. isto é, todo seu código JavaScript é válido em TypeScript (mas não o contrário). A principal diferença vai ser em relação a tipagem de dados, ao uso de classes, aos mecanismos de abstração, que são bem mais fortes.*

## Código exemplo de declaração de classe em JavaScript	
```javascript
class Retangulo {
  constructor(altura, largura) {
    this.altura = altura;
    this.largura = largura;
  }
}
```

## Código de exemplo de declaração de classe em TypeScript

```typescript 
class Pessoa {
	nome: string;
	idade: number;
	estaVivo: boolean;
	
	constructor(nome: string, idade: number, estaVivo: boolean){
		this.nome = nome;
		this.idade = idade;
		this.estaVivo = estaVivo;
	}
}
```

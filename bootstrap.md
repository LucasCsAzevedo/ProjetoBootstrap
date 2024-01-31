# Aula 1 - Introdução

# Bootstrap
- Framework ou biblioteca desenvolvimento
- Modular
- Componentes ricos
- CSS + JS
- Grid System
- Responsivo
- Mobile-first
- Amplamente utilizada
- Cross browser (Testadas em diferentes navegadores)

## Biblioteca x Framework
- Biblioteca: oferece objetos / classes prontas para uso
- Framework: oferece um conjunto de bibliotecas
- Biblioteca: recurso para trabalhar
- Framework: metodologia de trabalho
- Biblioteca: te leva ao destino
- Framework: te ensina a chegar

## Desenvolvimento ágil
- Metodologias: Scrum, Kanban, XP
- Entrega de valor para o negócio
- Ciclos evolutivos
- Não se repita (Não utiliza muitos "ifs")
- Separar grandes projetos em pequenas entregas (Meta e dividir em ações)
- MVP - Mínimo Produto Viável (Fazer um teste das pequenas fases para deixar o mais viável possível, evita o retrabalho)
- Estar envolvido x comprometido (Estar sempre com mind-set de aprender, evoluir)

## Vantagens
- Uso simples
- Menos código
- Abstração de estilos
- Documentação completa: https://getbootstrap.com/

## Desvantagens
- Uso excessivo
- Override de estilos (sobreposição)
- Abstração de estilos

### Com Bootstrap
```
<a class="btn btn-lg">Botão</a>
```

### Sem Bootstrap
```
<a class="botao botao-grande">

<style>
html {
    font-size: 62.5%
}

.botao {
    background-color: #ccc;
    border-radius: 2px;
    display: block;
    font-family: sans-serif;
    font-size: 1.6rem;
    padding: 1rem 2 rem;
    margin: 5px auto;
    ...
}

.botao.grande {
    font-size: 2rem;
}

.botao:hover { ... }
.botao:active { ... }
. botao:visited { ... }

</stile>

```

### MÓDULO 1

## Componentes
- Blocos / Modelos / Templates reutilizáveis https://getbootstrap.com/docs/5.1/components

## Helpers
- Funções básicas
- Incrementos
- Ajustes https://getbootstrap.com/docs/5.1/helpers

## Font Awesome
- Biblioteca de ícones https://fontawesome.com/start/

# Exercicio
- Incluir carousel na home antes de sobre
- Completar o cadastro, tornando os campos obrigatórios
- Incluir campos: bairro, complemento e telefone


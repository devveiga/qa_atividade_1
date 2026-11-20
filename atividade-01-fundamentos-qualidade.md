# Atividade 1: Fundamentos e Características da Qualidade no LocalEats

> Substituam os campos entre colchetes pelas respostas da equipe e removam as instruções antes da entrega.

## 1. Identificação

**Turma:** [preencher]
**Data:** [17/11/2026]

### Integrantes

| Nome | Usuário no GitHub |
|---|---|
| [Vitor Veiga] | [@devveiga] |

**Elemento de Competência:** Compreender os fundamentos de qualidade de software e sua aplicação no desenvolvimento de sistemas.

**Aplicação:** <https://local-eats-unisenac.vercel.app/>

---

## 2. Tarefa 1: Fundamentos da qualidade

### 2.1 Necessidades explícitas e implícitas

| Tipo | Necessidade | Interessado | Consequência se não for atendida |

Explícita	| Realizar | Pedido de Comida	Usuário	|	Perca de uma venda
Explícita	| Criar Conta	| Usuário	|	Devido ser fundamental para realizar o pedido, cliente não consegue realizar pedido. Desta forma, acaba por se perder uma venda.
Implícita	| Performance do Site	| Usuário	|	Experiência Ruim do usuário. Isto não implica de que naquele momento o cliente não realize o pedido, mas o faz repensar nas próximas vezes.
Implícita	| Responsividade	| Usuário	|	Experiência ruim do usuário. Espera-se que o site consiga de dispor de forma que não afete outros dispositivos com resoluções diferentes.

### 2.2 Questão sobre os fundamentos da qualidade

**Um sistema que implementa todas as funcionalidades explicitamente solicitadas pode, ainda assim, apresentar baixa qualidade? Justifiquem utilizando pelo menos uma necessidade implícita identificada pela equipe.**
Sim. Por exemplo: Responsividade
É uma necessidade implícita que o sistema deve possuir, e que se não cumprida, pode resultar na perca de algum cliente pela má experiência obtida na usabilidade do site.
Imagine a seguinte situação: Usuário quer realizar um pedido no sistema do restaurante. Entretanto, o usuário está acessando por celular, onde o tamanho da tela é diferente é menor, causando má disposição dos elementos do site.
Se o sistema não souber tratar a responsividade neste caso, fará com que o usuário perca a vontade pela má experiência obtida na navegação do site. O que em uma quantidade alta de usuários acessando o sistema se torna
significativamente preocupante a baixa retenção de usuários no site, consequentemente não realizando o ato final, que neste caso seria a realização do pedido.


---

## 3. Tarefa 2: Exploração da aplicação

> Cada integrante deve explorar uma funcionalidade, realizando uma utilização esperada e uma utilização alternativa, inválida ou incompleta. Acrescentem ou removam linhas conforme o número de integrantes.

| Integrante | Funcionalidade | O que foi realizado | O que foi observado | Evidência |
|---|---|---|---|---|
| Vitor Duarte Veiga | Filtro de Busca| Realizado busca por nome da Culinária e Localização | A barra descreve o campo de busca como "Buscar por culinária ou localização", entretanto, a busca filtra somente por Localização. Isto induz ao erro, já que a única forma de filtrar são nos buttons abaixo do campo de busca, que realizam o filtro pelas culinárias existentes. | [ver evidência](evidencias/filtro_busca_ambiguo.png) |

---

## 4. Tarefa 3: Requisitos e características de qualidade

> Cada integrante deve formular um requisito de qualidade relacionado à mesma funcionalidade explorada na Tarefa 2. Acrescentem ou removam linhas conforme o número de integrantes.

| Integrante | Requisito de Qualidade | Característica ou subcaracterística | Justificativa | Como avaliar |
|---|---|---|---|---|
| Vitor Duarte Veiga | Possibilitar o uso do campo de busca, aplicando filtros. | 1. Deve ser possível aplicar filtros pelos seguintes atributos: 1.1. Culinária 1.2. Localização Sugestão: Adicionar também Filtro por Estabelecimento (atualmente fora do escopo da funcionalidade) | Com o cumprimento do requisito, o usuário encontrará o registro alvo com mais facilidade e agilidade. | 1. Na seção Explorar, procure pelo Campo de Busca "Buscar por culinária ou localização"

1.1. Busque pelo nome da culinária

1.2. Busque por localização

Resultado: Deve retornar respectivamente todos os registros que possuem correspondências com os filtros aplicados. |

---

## 5. Uso de inteligência artificial

**Ferramenta utilizada:**  
Não Utilizada

**Como foi utilizada:**  
Não Utilizada

**Como as respostas foram verificadas:**  
Não Utilizada

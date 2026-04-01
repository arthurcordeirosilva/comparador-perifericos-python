#  Comparador Inteligente de Periféricos

## 📌 Descrição do Projeto
Este projeto tem como objetivo desenvolver um sistema em Python capaz de auxiliar usuários na escolha de periféricos (como mouse, teclado e headset), com base em seu perfil de uso e orçamento.

O sistema irá comparar produtos cadastrados em uma base de dados local, oferecendo recomendações personalizadas e destacando o melhor custo-benefício.

---

##  Problema
Muitos consumidores têm dificuldade em escolher periféricos adequados devido à grande variedade de opções no mercado, diferenças de preço e especificações técnicas complexas.

Além disso, é comum:
- pagar mais caro por um produto que não vale o preço
- ou comprar algo barato de baixa qualidade

---

##  Objetivo
Desenvolver uma aplicação que:
- filtre periféricos com base no perfil do usuário
- compare preços e características
- recomende a melhor opção de acordo com custo-benefício

---

##  Funcionalidades

###  Filtro de Produtos
- Filtrar por faixa de preço:
  - baixo
  - médio
  - alto
- Tipo de uso:
  - gamer
  - escritório

---

###  Sistema de Recomendação
O sistema irá sugerir produtos com base em critérios como:
- preço
- qualidade (simulada)
- marca

Cada produto receberá uma pontuação para definir o melhor custo-benefício.

---

###  Comparador de Preços
- Exibir:
  - menor preço
  - média de preços
- Alertas:
  - preço muito alto
  - preço muito baixo (possível risco)

---

###  Exibição de Resultados
- Lista de produtos recomendados
- Ordenação por custo-benefício

---

##  Base de Dados
Os dados dos produtos serão armazenados localmente em formato JSON.

Exemplo de estrutura:

```json
{
  "nome": "Mouse Gamer X",
  "preco": 120,
  "dpi": 8000,
  "marca": "Genérica",
  "categoria": "intermediario"
}
```
 ## Tecnologias Utilizadas
Python

JSON (armazenamento de dados)


 ## Melhorias Futuras
SQLite para melhor tratamento de dados

Interface web com o uso do Tkinter


##  Integrantes
1° Arthur Cordeiro Silva

2° Arthur Felipe Rodrigues

3° Felipe Henrique Ribeiro

4° Igor França Candido

5° Gabriel Alves

## Considerações Finais
Este projeto foi planejado com foco em simplicidade e funcionalidade, garantindo a entrega dentro do prazo, ao mesmo tempo em que permite expansão futura para um sistema mais complexo, faxendo o uso de outras tecnologias para aumentar sua performace.

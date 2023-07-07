# Teste - Angular NTT

O teste tem como objetivo acurar as habilidades do candidato em resolver alguns problemas relacionados à lógica de programação, regra de negócio e orientação à objetos.

O mesmo consiste em um cadastro de produtor rural com os seguintes dados:

1.  CPF ou CNPJ
2.  Nome do produtor
3.  Nome da Fazenda
4.  Cidade
5.  Estado
6.  Área total em hectares da fazenda
7.  Área agricultável em hectares
8.  Área de vegetação em hectares
9.  Culturas plantadas (Soja, Milho, Algodão, Café, Cana de Açucar)

# Requisitos de negócio

- O usuário deverá ter a possibilidade de cadastrar, editar, e excluir produtores rurais.
- O sistema deverá validar CPF e CNPJ digitados incorretamente.
- A soma de área agrícultável e vegetação, não deverá ser maior que a área total da fazenda
- Cada produtor pode plantar mais de uma cultura em sua Fazenda.
- A plataforma deverá ter um Dashboard que exiba:
  - Total de fazendas em quantidade
  - Total de fazendas em hectares (área total)
  - Gráfico de pizza por estado.
  - Gráfico de pizza por cultura.
  - Gráfico de pizza por uso de solo (Área agricultável e vegetação)

# Requisitos técnicos

- O desenvolvedor front-end deverá utilizar:
- 
  - [Angular](https://angular.io/);
  - [RxJS](https://rxjs.dev/)
  - pré-compiladores CSS (Sass, Less, etc.)
  - Crie pelo menos um teste unitário por componente (Opcional)
  - crie um BFF em [Node](https://nodejs.org/en) para consumo de dados pelo front
    - Os dados no BFF podem ser salvos numa lib de mock da sua preferência (não é necessário utilizar um banco de dados). ex: mock-server, json-server

 > Não envie a solução como anexo, suba os fontes para seu Github (ou outro repositório) e envie o link para o avaliador.


<img alt="Linear Sistemas" src="https://linearsistemas.com.br/wp-content/uploads/2020/09/marca-Linear-768x301.png" />

<h3 align="center">
  Teste 01
</h3>

<blockquote align="center">“Não espere para plantar, apenas tenha paciência para colher”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <a href="https://www.linearsistemas.com.br">
    <img alt="Made by Linear Sistemas" src="https://img.shields.io/badge/made%20by-Linear%20Sistemas-red">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#calendar-entrega">Entrega</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Nesse teste, você deve criar uma aplicação para atestar aquilo que discutido nas entrevistas!

Utilize a linguagem de programação que julgue ter mais domínio, para produção do resultado final.

As linguagens que serão melhores avaliadas pela Linear serão: 
 - <img src="https://img.shields.io/badge/visualbasic6-informational?logo=VB"></img>
 - <img src="https://img.shields.io/badge/vb.net-informational?logo=VB"></img>
 - <img src="https://img.shields.io/badge/csharp-informational?logo=C#"></img>
 - <img src="https://img.shields.io/badge/java-informational?logo=Java"></img>
 - <img src="https://img.shields.io/badge/node.js-informational?logo=Node.JS"></img>

O banco de dados a ser utilizado, precisa ser o MySQL 5.7.xxx. Você pode baixa-lo no link abaixo.
(https://dev.mysql.com/downloads/windows/installer/5.7.html)

Para avaliar as habilidades do(a) candidato(a) à vaga de Analista Desenvolvedor, será necessário que o mesmo implemente um projeto com um CRUD de pedidos de venda.

O projeto deve compreender uma interface gráfica para um simples sistema de pedidos de venda contendo:
 - LOGIN

<p align="center">
  <img src="./assets/login.png">
</p>

 - MENU PRINCIPAL
 
 <p align="center">
  <img src="./assets/menuPrincipal.png">
</p>

 - CADASTRO DE CLIENTE

<p align="center">
  <img src="./assets/clientes.png">
</p>

 - CADASTRO DE PRODUTO

<p align="center">
  <img src="./assets/produto.png">
</p>

 - CADASTRO DE PEDIDO DE VENDA.

<p align="center">
  <img src="./assets/pedido.png">
</p>

### Regras de Negócio

- Login

RN1: Não deve permitir logar ususário que não estejam cadastrados no banco de dados.
  
- Menu Principal

 o RN: N/A.

- Cadastro de Clientes

 o RN1: Não permitir excluir usuário que estejam referenciados em uma venda.

 o RN2: Não permitir gravar usuário sem o valor de limite de crédito, ou limite 0.

- Cadastro de Produtos

 o RN1: Não permitir gravar produtos sem o código,ou com código zerado.

 o RN2: Não permitir gravar produtos sem o preço, ou com preço zerado.
  
- Cadastro de Pedido de Venda

 o RN1: Não permitir gravar pedido para clientes cujo o valor do limite, ultrapasse o do cadastro de cliente.

 o RN2: Ao gravar um pedido, abater o valor total do pedido, no limite de crédito do cliente utilizado.

 o RN3: Não permitir inserção de produtos com preço de venda zerados.

Se dividirmos semânticamente as responsabilidades da nossa aplicação em entidades, considere separar as regras de negócio, da camada de visão.

Bons estudos <3

## :calendar: Entrega

Esse desafio deve ser entregue por email, na qual ele deve contar o link do seu repositório do Git Hub, com o projeto.

Não se esqueça de montar um arquivo README.MD incrível, nos explicando as tecnologias usadas, dependências do projeto e como subir a sua aplicação. 😉

Caso precise de uma ajuda em como montar um README.MD nos moldes convencionais, dê uma olhada neste perfil.
(https://github.com/thiagokrathos/go-restaurant-mobile)

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](../LICENSE) para mais detalhes.

---

Feito com 💜 by Rocketseat :wave: [Entre na nossa comunidade!](https://discordapp.com/invite/gCRAFhc)

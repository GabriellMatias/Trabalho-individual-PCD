# 🚀 Projeto de Programação Concorrente e Distribuída
Este projeto simula compras em lojas, intermediadas por um banco, onde funcionários recebem salários e investem parte do valor.

## ℹ️ Descrição
O sistema simula compras em várias lojas, onde clientes gastam em compras de R$100,00 ou R$200,00, alternando entre as lojas até que o saldo da conta esteja vazio. Cada loja possui uma conta para receber pagamentos dos clientes e pagar funcionários, que recebem salários de R$1.400,00.

Cada funcionário é uma thread e possui duas contas: uma para receber o salário da loja e outra de investimentos. Após receber o salário, o funcionário investe 20% do valor na conta de investimentos.

O banco atua como intermediário nas transações, garantindo a consistência dos saldos das contas. O sistema exibe transferências e saldos finais de cada conta.

## ⚙️ Componentes
 - Loja: Recebe pagamentos e paga funcionários.
 - Funcionário: Recebe salário e investe.
 - Banco: Intermedia transações e garante consistência de saldos.
## 📝 Instruções
Compile o projeto com Java 17.
Execute o programa principal para iniciar a simulação.
Observe transações e saldos exibidos ao final.
## 🛠️ Pré-requisitos
JDK 17 ou superior
Ambiente de desenvolvimento Java
## ✍️ Autores
[GabriellMatias]([link para o seu perfil no GitHub](https://github.com/GabriellMatias))
## 📄 Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE.md para detalhes.

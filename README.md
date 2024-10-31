ank Virtual - Banco Virtual Simulado
Este projeto simula um sistema de banco virtual, com funcionalidades para gerenciar contas corrente e poupança, inserir salários, realizar transações PIX e visualizar o saldo. Foi desenvolvido usando Python com Flask para o backend e HTML/CSS para o frontend, com uma interface organizada e intuitiva.

📋 Funcionalidades Principais
Depósito de Salário: Interface para o usuário inserir o salário diretamente no sistema.
Conta Corrente e Conta Poupança:
Opções de depósito e saque em ambas as contas.
A conta poupança possui restrições para que o saldo transferido não ultrapasse o saldo disponível da conta corrente.
Transação via PIX:
Geração de QR Code para simular uma transferência PIX.
O usuário pode escanear o QR Code para adicionar valores à conta automaticamente.
🚀 Tecnologias Utilizadas
Backend: Python com Flask
Frontend: HTML e CSS
Geração de QR Code: Biblioteca qrcode
📂 Estrutura de Pastas
plaintext
Copiar código
bank/
├── app.py                   # Arquivo principal do aplicativo Flask
├── templates/               # Diretório dos templates HTML
│   ├── index.html           # Página inicial e menu
│   ├── conta_corrente.html  # Página de operações de conta corrente
│   ├── conta_poupanca.html  # Página de operações de conta poupança
│   ├── salario.html         # Página de depósito de salário
├── static/
│   ├── style.css            # Estilos para o frontend
│   ├── qrcode.png           # QR Code gerado para transações PIX
└── README.md                # Arquivo de descrição do projeto
⚙️ Pré-requisitos
Python 3.x: Certifique-se de ter o Python instalado.
Bibliotecas Python:
bash
Copiar código
pip install flask qrcode[pil]
🛠️ Como Executar
Clone o repositório:
bash
Copiar código
git clone https://github.com/abreujoao/bank.git
cd bank
Execute o aplicativo:
bash
Copiar código
python app.py
Abra o navegador e acesse http://localhost:5000.
📲 Simulação de PIX
Na seção "PIX" da página inicial:

Insira o valor desejado e clique em "Gerar QR Code".
Escaneie o QR Code gerado para simular a adição do valor à conta.

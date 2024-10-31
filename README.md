# Bank Virtual - Banco Virtual Simulado

Este projeto simula um sistema de banco virtual, com funcionalidades para gerenciar contas corrente e poupança, inserir salários e visualizar o saldo. Foi desenvolvido usando Python com Flask para o backend e HTML/CSS para o frontend, com uma interface organizada e intuitiva.

## 📋 Funcionalidades Principais

- **Depósito de Salário**: Interface para o usuário inserir o salário diretamente no sistema.
- **Conta Corrente e Conta Poupança**:
  - Opções de depósito e saque em ambas as contas.
  - A conta poupança possui restrições para que o saldo transferido não ultrapasse o saldo disponível da conta corrente.

## 🚀 Tecnologias Utilizadas

- **Backend**: Python com Flask
- **Frontend**: HTML e CSS

```

## ⚙️ Pré-requisitos

- **Python 3.x**: Certifique-se de ter o Python instalado.
- **Bibliotecas Python**:
  ```bash
  pip install flask qrcode[pil]
  ```

## 🛠️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/abreujoao/bank.git
   cd bank
   ```
2. Execute o aplicativo:
   ```bash
   python app.py
   ```
3. Abra o navegador e acesse `http://localhost:5000`.

## 📲 No Futuro - Inserção de QRCODE para PIX

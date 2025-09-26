# 💰 Coin App (Clone em Flutter)

Este projeto é uma **aplicação Flutter** desenvolvida como estudo e referência ao design do aplicativo **Coin**.  
O objetivo é praticar **UI design no Flutter**, organizar widgets reutilizáveis e integrar a biblioteca **Device Preview** para testar em diferentes resoluções de dispositivos móveis.

---

## 🚀 Funcionalidades

- Tela inicial com:
  - Saudação personalizada ao usuário.
  - Saldo atual exibido em destaque.
  - Lista de transações recentes.
- Cards de transação com:
  - Nome do estabelecimento.
  - Categoria da compra.
  - Valor gasto formatado.
- **Floating Action Button** para adicionar novas transações.
- Tema customizado com cores baseadas no app Coin.
- Suporte ao **Device Preview** para visualizar em diferentes dispositivos.

---

## 📸 Preview

> Interface inspirada no aplicativo Coin.  
> (Exemplo de design utilizado como referência)

![Preview do Coin App](WhatsApp%20Image%202025-09-25%20at%2023.45.34.jpeg)

---

## 📂 Estrutura do Código

- **main.dart**  
  - Configuração do `DevicePreview`.
  - Definição do tema global do app.
  - Tela inicial (`CoinHomePage`).

- **CoinHomePage**  
  - Exibe saldo atual.
  - Saudação personalizada.
  - Lista de transações do dia.

- **Transaction & TransactionCard**  
  - Modelo simples de dados (`Transaction`).
  - Componente visual reutilizável (`TransactionCard`) para exibir cada transação.

---

## 🛠️ Tecnologias Utilizadas

- **[Flutter](https://flutter.dev/)**
- **Dart**
- **Device Preview** (`device_preview`)

---

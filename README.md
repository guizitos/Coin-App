#  Coin App (Clone em Flutter)

Este projeto é uma **aplicação Flutter** desenvolvida como estudo e referência ao design do aplicativo **Coin**.  
O objetivo é praticar **UI design no Flutter**, organizar widgets reutilizáveis e integrar a biblioteca **Device Preview** para testar em diferentes resoluções de dispositivos móveis.

---


##  Preview

> Interface inspirada no aplicativo Coin.  
> (Exemplo de design utilizado como referência)

![Preview do Coin App](WhatsApp%20Image%202025-09-25%20at%2023.45.34.jpeg)

> (Como a aplicação ficou de acordo com a referência)

![Aplicação Flutter](Captura%de%tela_25-9-2025_234414_localhost.jpeg)

---

##  Estrutura do Código

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

##  Tecnologias Utilizadas

- **[Flutter](https://flutter.dev/)**
- **Dart**
- **Device Preview** (`device_preview`)

---

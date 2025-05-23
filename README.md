# Sistema de Biblioteca - Análise e Refatoração

## Parte 1: Violações Identificadas

1. **SRP violado na classe `GerenciadorBiblioteca`** – concentra múltiplas responsabilidades.
2. **OCP violado nos métodos de empréstimo** – difícil extender notificações.
3. **DIP violado pela ausência de abstrações** – notificação fortemente acoplada.
4. **Métodos grandes e com múltiplas responsabilidades** – baixa legibilidade e manutenção.
5. **Falta de segregação de interfaces (ISP)** – ausência de contratos específicos para dependências.

## Parte 2: Refatoração

Refatoramos o sistema com aplicação dos princípios SOLID e boas práticas de Clean Code:
- Separação de responsabilidades (serviços, notificadores, entidades)
- Uso de interfaces para notificadores (DIP e OCP)
- Métodos curtos e focados

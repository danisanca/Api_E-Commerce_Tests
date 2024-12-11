# 📊 Projeto de Testes da API E-Commerce

Repositório de testes automatizados para validar as funcionalidades da [API E-Commerce](https://github.com/danisanca/Api_E-Commerce). 
Este projeto foi desenvolvido para garantir a **integridade e confiabilidade** da aplicação, cobrindo diferentes camadas da API com testes unitários.

---

## 📄 Descrição
O objetivo deste projeto é assegurar que todas as funcionalidades implementadas na API estejam funcionando conforme esperado. Os testes incluem validações de regras de negócio, persistência de dados e mapeamento de objetos.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
- **xUnit**: Framework para criação e execução de testes unitários.
- **AutoMapper**: Para validar o mapeamento entre DTOs e Models.
- **Faker.NetCore**: Geração de dados fictícios para simulação de entradas.
- **Moq**: Mocking framework para simulação de dependências e comportamento.

---

## 🧪 Escopo dos Testes
Os testes foram desenvolvidos para verificar as seguintes camadas da aplicação:

1. **Controllers**:
   - Garantir a integridade das informações recebidas.
   - Validar os retornos esperados, como `Ok` ou `BadRequest`.

2. **Repositórios e Banco de Dados**:
   - Certificar que os dados estão sendo persistidos corretamente no banco de dados.

3. **Serviços (Services)**:
   - Validar as regras de negócio e os retornos com base nos parâmetros de entrada.
   - Simular dependências e dados de retorno utilizando **Moq**.

4. **Mapeamento de Dados (AutoMapper)**:
   - Garantir a consistência no mapeamento entre **DTOs** e **Models**.

---

## 🚀 Entidades Testadas
- **Usuário**: 
  - Os testes iniciais focaram na entidade `Usuário`.
  - **Próximos Passos**: Expandir a cobertura para as demais entidades da aplicação, seguindo a abordagem detalhada acima.

---

## 📂 Estrutura do Repositório
tests/ │-- Controllers/ │-- Repositories/ │-- Services/ 

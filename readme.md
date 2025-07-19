# 📦 Busca de Endereço por CEP

<img src="logo.png" width="350" height="200"/>

Este é um servidor baseado no **Model Context Protocol (MCP)** que permite buscar endereços brasileiros a partir de um número de CEP, retornando informações formatadas e amigáveis para modelos de linguagem (LLMs).

## ✨ Funcionalidades

- 🔍 **Busca por CEP:** Consulta a API do ViaCEP para obter os dados detalhados de um endereço.
- 🧠 **Resposta Formatada:** Retorna o endereço de forma clara e resumida (logradouro + bairro + cidade + UF), ideal para consumo por agentes de IA.
- ⚙️ **Stateless & Plug-and-Play:** Projeto sem estado, pronto para ser conectado a qualquer agente MCP.
- 🛡️ **Validação com Zod:** Garante a integridade dos dados com schemas robustos.
- 💬 **Mensagens Amigáveis para LLMs:** A resposta é estruturada para facilitar o entendimento por agentes conversacionais.

## 🧪 Exemplo de Uso

Input:

- Busque o nome da cidade correspondente ao CEP 06755-260
- Busque o CEP 06755-260
- @buscar_cep 06755260
- @buscar_cep 06755-260
- @buscar_cep 06755-260 e formate o resultado em tabela

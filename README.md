# TripleTen_Analyst_QA_Sprint_04_Teste_de_API

# Sprint 04 - Teste de APIs - Roberth Guimaro

Este repositório reúne os materiais, coleções e evidências desenvolvidas na Sprint 04 do curso de QA, com foco em **teste de APIs (Application Programming Interfaces)**.  
O objetivo foi entender os fundamentos, aplicar testes manuais em APIs REST e gerar documentação e relatórios de qualidade.

---

## Conteúdo da Sprint

### Fundamentos de APIs
- Conceitos básicos: o que são APIs e como funcionam.  
- Arquitetura REST e métodos HTTP (GET, POST, PUT, DELETE).  
- Estrutura de requisições e respostas.  
- Códigos de status HTTP e seus significados.  

### Ferramentas de Teste
- Uso do **Postman** para teste manual de APIs.  
- Criação e organização de coleções.  
- Configuração de ambientes e variáveis.   

### Tipos de Teste de API
- **Testes funcionais**: validação de endpoints.  
- **Testes de dados**: verificação de payloads JSON/XML.  
- **Testes de performance básicos**.  
- **Testes de segurança e autenticação**.  

### Validação e Documentação
- Análise de documentação de API (Swagger/OpenAPI).  
- Validação de esquemas de dados.  
- Criação de casos de teste específicos para APIs.  
- Relatórios de bugs relacionados a APIs.  

---

## Estrutura do Repositório

```/
├── Kits_API/
│   ├── Adicionar_itens_ao_kit_API/ ← Documentação relacionada a API
│   ├── Alterar_kit_API/ ← Documentação relacionada a API
│   ├── Criar_um_kit_API/ ← Documentação relacionada a API
│   ├── Excluindo_kit_API/ ← Documentação relacionada a API
│   ├── Obter_todos_os_kits_API/ ← Documentação relacionada a API
│   ├── Obter_um_kit_pelo_nome_API/ ← Documentação relacionada a API
│   ├── Casos_de_testes_kit_API.xlsx ← Casos de teste planejados e executados para kits, junto do link para o `Jira` com o reporte dos BUGs encontrados
│   ├── Conjunto_valor_intervalo_kit_API.xlsx ← Testes de intervalo/valores para kits
│   └── Requisitos_para_o_back-end_do_urban.grocers.pdf ← Documento de requisitos do backend
│
├── Order_and_go_API/
│   ├── Casos_de_testes_order_and_go_API.xlsx ← Casos de teste planejados e executados para pedidos (order and go), junto do link para o `Jira` com o reporte dos BUGs encontrados 
│   ├── Conjunto_valor_intervalo_order_and_go_API.xlsx ← Testes de valores/intervalos para pedidos (order and go)
│   ├── Order_and_go_API.png ← Documentação relacionada a API
│   └── Os_requisitos_para_calcular_a_entrega_via_servicos_de_entrega.pdf ← Documento de requisitos de cálculo de entrega
│
├── kit_and_order_and_go_API.postman_collection.json ← Coleção Postman com todos os endpoints de kits e pedidos, relacionados pelo numero ID
│
└── README.md ← Documentação atual
```

---

## Como usar 

1. **Importar as coleções do Postman** 
   (Obs.: Não será possível realizar os testes sem o server_url atualizado, por isso, atualize a variavel de ambiente no postman)
   - Vá em `File > Import` no Postman e selecione os arquivos em `Coleções_Postman/`.  
   - Configure os ambientes e variáveis antes de executar os requests.  

2. **Executar os testes**  
   - Utilize os requests organizados nas coleções para validar endpoints.  
   - Compare as respostas com os **casos de teste em `Casos_de_teste_APIs.xlsx`**.  

3. **Validar resultados**  
   - Verifique payloads (JSON/XML), códigos de status e mensagens de erro.  
   - Registre inconsistências em `Relatorios_de_bugs.xlsx`.  
   - Gere os registros das inconsistências no `Jira` e relacione na tabela citada acima.  

4. **Consultar documentação**  
   - Use links de Swagger/OpenAPI fornecidos pela API para rastrear requisitos.  
   - Garanta que todos os endpoints possuam cobertura de teste.

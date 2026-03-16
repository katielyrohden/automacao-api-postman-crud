# Automação e Validação de API REST: E-commerce Alfajor Artesanal

## Sobre o Projeto
Este repositório apresenta um projeto prático de testes de Backend (End-to-End) simulando o fluxo de um sistema de e-commerce. Como profissional com sólida experiência em testes manuais e liderança de equipes de QA, este projeto marca a minha consolidação técnica na automação de processos para garantir entregas mais robustas e eficientes.

## Tecnologias e Ferramentas Utilizadas
* **Postman:** Ferramenta principal para criação de coleções e execução de testes.
* **JavaScript (Scripts de Automação):** Utilizado para captura de respostas JSON e manipulação de variáveis globais.
* **APIs REST:** Validação de verbos HTTP e conformidade de contratos.
* **SQL (Conhecimento Lógico):** Estruturação de consultas para auditoria e integridade de dados no banco de dados.
* **GitHub:** Versionamento de artefatos de teste e documentação técnica.

## Cenários de Teste Executados (CRUD Completo)
A coleção incluída neste projeto cobre o ciclo de vida completo de um recurso:

1. **Criação (POST):** Cadastro de novos clientes e produtos.
   * *Validação:* Status Code `201 Created` e análise do Payload de retorno.
2. **Leitura (GET):** Consulta de dados específicos por ID.
   * *Validação:* Status Code `200 OK`.
3. **Atualização (PUT):** Alteração de informações em registros existentes.
   * *Validação:* Status Code `200 OK` e confirmação da persistência dos dados.
4. **Exclusão (DELETE):** Remoção de dados do sistema.
   * *Validação:* Status Code `200 OK`.
5. **Caminhos Tristes (Testes de Resiliência):** Busca por IDs inexistentes para validar o tratamento de erros.
   * *Validação:* Status Code `404 Not Found`.

## Diferencial Técnico: Automação de Fluxo
Para otimizar a esteira de testes, utilizei scripts na aba **Post-res** (Tests) do Postman. O sistema captura automaticamente o `id` gerado no método POST e o armazena na variável `{{meu_novo_id}}`. Dessa forma, os testes de atualização (PUT) e exclusão (DELETE) são alimentados dinamicamente, eliminando a necessidade de intervenção manual entre as requisições.

## Sobre a Autora
**Katiély Rohden**
Especialista em Qualidade de Software com foco em liderança de equipes e documentação de processos. Atualmente em transição estratégica para o mundo da automação, unindo a visão crítica do teste manual com a eficiência técnica do código para elevar o padrão de qualidade das soluções de software.

---
*Para reproduzir estes testes, basta importar o arquivo `.json` presente neste repositório para o seu Postman.*

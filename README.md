# Automação de Testes de API REST: JSONPlaceholder (CRUD Completo)

## Sobre o Projeto
Este repositório contém um projeto prático de automação de testes de Backend utilizando a API pública **JSONPlaceholder**. O objetivo é demonstrar a validação do ciclo de vida completo de um recurso (usuários), aplicando técnicas de verificação de Status Codes, contratos de resposta e automação de fluxos dinâmicos.

Como profissional com experiência consolidada em testes manuais e liderança de QA, este projeto reflete minha transição para o stack de automação, garantindo que a lógica de teste seja aplicada de forma eficiente e escalável.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Postman:** Para testes manuais, exploratórios e automação de requisições.
* **JavaScript (Postman Scripts):** Para captura de respostas (JSON) e criação de variáveis dinâmicas.
* **APIs REST:** Validação de verbos HTTP e arquitetura.
* **SQL (Simulação mental/validação):** Estruturação de consultas (`SELECT`, `WHERE`) para auditoria de banco de dados.
* **Swagger/Documentação:** Leitura e mapeamento de endpoints e contratos de API.

## 🧪 Cenários de Teste Executados (CRUD Completo)
A coleção do Postman neste repositório cobre os seguintes cenários:

1. **Criação (POST):** Cadastro de novos clientes e produtos.
   * *Validação:* Status Code `201 Created` e confirmação do Payload (Body).
2. **Leitura (GET):** Consulta de produtos específicos por ID.
   * *Validação:* Status Code `200 OK`.
3. **Atualização (PUT):** Alteração de preços e dados de clientes.
   * *Validação:* Status Code `200 OK` e conferência da atualização.
4. **Exclusão (DELETE):** Remoção de itens do catálogo.
   * *Validação:* Status Code `204 No Content` ou `200 OK`.
5. **Caminhos Tristes (Testes Negativos):** Busca por IDs inexistentes.
   * *Validação:* Status Code `404 Not Found`.

## 🤖 Automação Destacada
Para otimizar a execução, este projeto utiliza **Variáveis de Ambiente e Globais**. 
Através da aba *Tests* do Postman, o script captura dinamicamente o `id` gerado no método POST e guarda numa variável `{{meu_novo_id}}`, passando a informação automaticamente para os testes seguintes (PUT e DELETE), criando uma esteira de testes contínua e sem necessidade de intervenção manual.

## Sobre a Autora
**Katiély Rohden**
Especialista em Qualidade de Software com foco em liderança de equipes e documentação de processos. Atualmente em transição estratégica para o mundo da automação, unindo a visão crítica do teste manual com a eficiência técnica do código para elevar o padrão de qualidade das soluções de software.

---
*Para reproduzir estes testes, basta importar o arquivo `.json` presente neste repositório para o seu Postman.*

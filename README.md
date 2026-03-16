# Automação de Testes de API REST: JSONPlaceholder (CRUD Completo)

## Sobre o Projeto
Este repositório contém um projeto prático de automação de testes de Backend utilizando a API pública **JSONPlaceholder**. O objetivo é demonstrar a validação do ciclo de vida completo de um recurso (usuários), aplicando técnicas de verificação de Status Codes, contratos de resposta e automação de fluxos dinâmicos.

Como profissional com experiência consolidada em testes manuais e liderança de QA, este projeto reflete minha transição para o stack de automação, garantindo que a lógica de teste seja aplicada de forma eficiente e escalável.

## Tecnologias e Ferramentas Utilizadas
* **Postman:** Criação e organização da suíte de testes (Collections).
* **JavaScript (Scripts de Automação):** Scripts na aba "Tests" para validação e captura de variáveis.
* **JSONPlaceholder API:** Endpoint público utilizado para simulação de ambiente real.
* **GitHub:** Documentação e versionamento do projeto.

## Cenários de Teste Executados
A coleção valida as quatro operações principais (CRUD):
1. **POST - Criar Usuário e Capturar ID:** Valida a criação (201) e automatiza a captura do ID para os testes seguintes.
2. **GET - Consultar Usuário por ID:** Valida se o retorno é 200 OK para um ID existente.
3. **PUT - Atualizar Dados:** Simula a alteração de informações do usuário.
4. **DELETE - Excluir Usuário:** Valida a remoção do registro.
5. **GET - Validar Erro 404:** Testa a resiliência da API ao buscar um recurso inexistente.

## Sobre a Autora
**Katiély Rohden**
Especialista em Qualidade de Software com foco em liderança de equipes e documentação de processos. Atualmente em transição estratégica para o mundo da automação, unindo a visão crítica do teste manual com a eficiência técnica do código para elevar o padrão de qualidade das soluções de software.

---
*Para reproduzir estes testes, basta importar o arquivo `.json` presente neste repositório para o seu Postman.*

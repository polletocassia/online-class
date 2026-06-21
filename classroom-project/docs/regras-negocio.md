# Regras de Negócio

## RN01 – Somente professores podem criar turmas.

**User Story:** Como professor, quero criar uma turma para organizar meus alunos.

**Caso de Uso:** Criar Turma.

**BPMN:** A tarefa "Criar Turma" é executada exclusivamente pelo professor.

**Arquitetura:** Controle de permissões baseado em perfil de usuário.

**Requisito Não Funcional:** Segurança e controle de acesso.

---

## RN02 – Alunos só podem acessar turmas nas quais estão matriculados.

---

## RN03 – Somente professores podem cadastrar atividades.

---

## RN04 – Atividades possuem prazo de entrega.

---

## RN05 – Após o prazo, a atividade é marcada como atrasada.

**User Story:** Como professor, quero publicar atividades para avaliar meus alunos.

**Caso de Uso:** Registrar Entrega.

**BPMN:** Representado por um Timer Boundary Event (Non-Interruptive).

**Arquitetura:** Rotina automática de comparação entre data de entrega e prazo.

**Requisito Não Funcional:** Automação e precisão dos dados.

---

## RN06 – Professores podem corrigir manualmente ou utilizar correção automática por IA.

---

## RN07 – A pontuação da gamificação é atualizada após a entrega das atividades.

---

## RN08 – Alunos não podem alterar notas.

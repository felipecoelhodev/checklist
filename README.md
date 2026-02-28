# Checklist

Um gerenciador de tarefas minimalista e eficiente, focado na organização de estudos. O projeto permite criar, editar, excluir e marcar tarefas como concluídas, mantendo os dados salvos localmente para garantir que seu progresso não seja perdido.



## Funcionalidades

* **Gestão de Tarefas:** Adicione novos tópicos de estudo rapidamente.
* **Edição Flexível:** Altere a descrição de tarefas existentes através de um diálogo modal.
* **Organização Visual:** Divisão automática entre itens "Para estudar" e "Concluídos".
* **Persistência de Dados:** Utiliza `localStorage` para manter suas tarefas salvas no navegador.
* **Interface Responsiva:** Design moderno com tema dark e componentes personalizados (FAB, Modais, Inputs).

## Tecnologias Utilizadas



* **React 19:** Utilizando o hook `use` para consumo de contextos.
* **Vite:** Build tool ultra-rápida para o desenvolvimento.
* **Context API:** Gerenciamento de estado global centralizado no `TodoProvider`.
* **CSS Modules (Custom):** Estilização modularizada para componentes reutilizáveis.
* **HTML5 Dialog API:** Implementação nativa de modais para melhor acessibilidade.

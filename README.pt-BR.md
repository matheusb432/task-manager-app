# Task Manager App

Aplicação web Fullstack para gerenciar tarefas e medir métricas de produtividade.

O aplicativo possui uma versão de demonstração sem integração de back-end, hospedada no Vercel. Você pode acessá-la [aqui](https://task-manager-app-fake-backend.vercel.app/home/).

## Repositórios

- TMA API - .NET
- TMA SPA - Angular

## Principais Recursos

- CRUD para tarefas, perfis e quadros de horários;
- Sistema de autenticação sólido utilizando JWT;
- Layout responsivo para todos os dispositivos e design seguindo as melhores práticas de UX;
- Criação de perfis de produtividade com flexibilidade de agendamento, seja para intervalos específicos, dias úteis ou fins de semana (por exemplo, definir uma meta para estudar 5 horas por dia durante o mês de julho);
- Adicionar tarefas predefinidas aos perfis (por exemplo, incluir uma atividade relacionada ao trabalho nos dias úteis e adicionar uma atividade para o seu projeto pessoal nos fins de semana);
- Visualizar métricas em um calendário interativo, indicando o cumprimento de suas metas em dias específicos;
- Visualizar métricas em intervalos de datas, com informações resumidas sobre seu progresso.

## Telas principais

![Home](./images/home.png 'Tela home')

### Timesheets

![Lista com calendário interativo](./images/timesheets.png 'Lista de timesheets')
![Formulário de timesheet](./images/timesheet-form.png 'Formulário de timesheet')
![Métricas](./images/metrics.png 'Métricas')

### Perfis

![Página de criação](./images/profiles.png 'Página de criação de perfis')
![Página de tarefas pré-definidas](./images/tasks.png 'Página de tarefas pré-definidas')

### FAQs

![Tela de FAQs](./images/faqs.png 'Tela de FAQs')

## Funcionalidades de UI/UX

### Validação reativa de formulários

![Validação reativa de formulários](./images/reactive-validation.png 'Validação reativa de formulários')

### Prevenção de alterações não salvas

![Prevenção de alterações não salvas](./images/unsaved-changes-dialog.png 'Modal de prevenção de alterações não salvas')

### Layouts responsivos

![Layout responsivo de perfis](./images/profiles-mobile.png 'Tela de perfis em dispositivos móveis')
![Layout responsivo de métricas](./images/metrics-mobile.png 'Tela de métricas em dispositivos móveis')

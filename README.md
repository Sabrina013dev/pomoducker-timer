# PomoDucker

## 1. Introdução

O PomoDucker é uma aplicação web que auxilia os usuários a gerenciarem seu tempo de foco e descanso, utilizando a técnica Pomodoro. A aplicação permite configurar os tempos de foco e descanso de forma personalizada e em versões futuras, terá a funcionalidade de gerenciamento de tarefas (tasks).

## 2. Objetivo

O objetivo é fornecer uma ferramenta simples e eficaz para aumentar a produtividade através da técnica Pomodoro, permitindo que o usuário ajuste os períodos de foco e descanso conforme sua necessidade.

## 3. Tecnologias

- **HTML:** Estrutura da aplicação;
- **CSS:** Estilização da interface;
- **Javascript Vanilla:** Lógica do timer e interatividade da aplicação;
- **Backend:** Java (Spring Boot);
- **Banco de Dados:** MySQL. 

## 4. Funcionalidades

### Funcionalidades da Versão Inicial

- **Timer Perzonalizável:** Permite que o usuário ajuste os tempos de foco e descanso.
- **Iniciar/Pausar/Redefinir o Timer:** Controles básicos para o funcionamento do Pomodoro.
- **Alerta sonoro:** Aviso ao final dos períodos de foco e descanso.

### Funcionalidades Futuras (Próximas versões)

- **Gerenciamento de Tarefas:** Permite que o usuário crie, edite e conclua tarefas associadas a cada ciclo Pomodoro.
- **Histórico de Produtividade:** Registrar os ciclos concluídos e o tempo total de foco diário.

# 5. Requisitos

## Requisitos Funcionais 
- RF01: O sistema deve permitir que o usuário defina o tempo de foco (em minutos).
- RF02: O sistema deve permitir que o usuário defina o tempo de descanso (em minuto).
- RF03: O sistema deve iniciar, pausar e redefinir o timer.
- RF04: O sistema deve emitir um alerta sonoro ao final de cada ciclo (foco/descanso).
- RF05 (Futuro): O sistema deve permitir a criação e gerenciamento de tasks.

## Requisitos Não Funcionais
- RNF01: O sistema deve ser responsivo e adaptável a diferentes dispositivos.
- RNF02: A interface deve ser simples e intuitiva.
- RNF03: O desempenho do timer deve ser preciso, com variação máxima de 1 segundo.

# 6. Prototipagem e interface

A interface será projetada inspirada na figura de um patinho com uma pegada animada e minimalista, com destaque para o timer e os controles principais. Em futuras versões, a seção de tasks será integrada de forma harmoniosa na interface.

# 7. Conclusão

O Pomodoro Timer visa oferecer uma experiência fluida e eficaz para quem deseja utilizar a técnica Pomodoro no seu dia a dia. Com a implementação inicial focada no timer e, posteriormente nas tasks, o software se adaptará ao crescimento das necessidades do usuário.

![Banner PomoDucker](/images/pomodoro%20timer.png)

# 8. Instalação e Execução

## Clone o repositório:

git clone https://github.com/Sabrina013dev/pomoducker-timer.git

### Acesse a pasta do projeto:

cd pomodoro-web

### Instale as dependências:

npm install

### Inicie o servidor de desenvolvimento:

npm start

### Contribuição

- Fork o repositório

- Crie um branch para sua feature (git checkout -b minha-feature)

- Commit suas alterações (git commit -m 'Adicionando nova feature')

- Envie um PR (Pull Request) para revisão

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.


# Ananke App

Academy Organizer é um aplicativo desenvolvido em React Native com Expo, destinado a auxiliar na organização de horários acadêmicos. Ele permite que administradores, professores e alunos visualizem e gerenciem horários de aulas, cursos e disponibilidade de professores de forma intuitiva e eficiente.

## Funcionalidades

- **Cadastro de Cursos e Matérias**: Permite que o usuário cadastre cursos e as respectivas matérias.
- **Cadastro de Professores**: Facilita o cadastro de professores, incluindo as matérias que lecionam e sua disponibilidade.
- **Montagem da Grade de Horários**: O aplicativo organiza automaticamente a grade de horários com base na disponibilidade dos professores e nas matérias dos cursos.

  ## Pastas
  ```javascript
/AcademyOrganizer
|-- /assets
|   |-- /images
|   |-- /fonts
|-- /components
|   |-- /Button
|   |   |-- index.js
|   |   |-- styles.js
|   |-- /Card
|       |-- index.js
|       |-- styles.js
|-- /screens
|   |-- /Home
|   |   |-- index.js
|   |   |-- styles.js
|   |-- /CourseRegistration
|   |   |-- index.js
|   |   |-- styles.js
|   |-- /TeacherRegistration
|   |   |-- index.js
|   |   |-- styles.js
|   |-- /ScheduleBuilder
|       |-- index.js
|       |-- styles.js
|-- /navigation
|   |-- index.js
|-- /constants
|   |-- colors.js
|   |-- styles.js
|-- /hooks
|   |-- useCourses.js
|   |-- useTeachers.js
|-- /context
|   |-- CourseContext.js
|   |-- TeacherContext.js
|-- /api
|   |-- coursesApi.js
|   |-- teachersApi.js
|-- /utils
|   |-- helperFunctions.js
|-- App.js
|-- app.json


## Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)
- AsyncStorage para armazenamento local
- Outras bibliotecas e frameworks conforme necessário

## Instalação

Para executar o Academy Organizer localmente, siga estas etapas:

1. Clone o repositório: https://github.com/Eduardo1985S/ananke.git


# Folder Structure Conventions

Estrutura padrão de pastas padrão para projetos em C#

### Crie um solução em branco chamada FolderStructureConventions

Adicione um novo projeto do tipo Blank solution

### Adicione um novo projeto

O nome do projeto deve ser nomeado como Namespace.CamadaOuFinalidade e a pasta de destino do projeto deve ser definida em Location como (pasta da solução)\src

#### Exemplo

C:\GitHub\FolderStructureConventions\src

### Adicione um novo projeto de testes

O nome do projeto deve ser nomeado como Namespace.CamadaOuFinalidade.Tests e a pasta de destino do projeto deve ser definida em Location como (pasta da solução)\tests

#### Exemplo

C:\GitHub\FolderStructureConventions\tests

### Altere a pasta de builds dos projetos

Clique com o botão direito sobre o projeto, em seguida em Properties,
Clique em Build,
Em Configuration, selecione Debug,
Em Output path digite (pasta da solução)\build\\(NomeDoProjeto)\Debug,
Em Configuration, selecione Release,
Em Output path digite (pasta da solução)\build\\(NomeDoProjeto)\Release.

#### Exemplo

C:\GitHub\FolderStructureConventions\build\FolderStructureConventions.Prompt\Debug

ou

..\..\build\FolderStructureConventions.Prompt\Debug

### Exclua todas as pastas bin
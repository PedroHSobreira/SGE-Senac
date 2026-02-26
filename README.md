📚 Sistema de Gerenciamento Escolar com Laravel
PHP Laravel HTML CSS JavaScript Bootstrap SQLite

📌 O Senac App é um Sistema de Gerenciamento Escolar (SGE) desenvolvido como parte do Projeto Integrador do curso Técnico em Informática no Senac São Bernardo do Campo.

A aplicação foi construída utilizando Laravel com arquitetura MVC, com o objetivo de centralizar e automatizar processos acadêmicos como cadastro de alunos, docentes, cursos, turmas e avaliações.

O sistema implementa controle de autenticação para diferentes perfis (Administrador, Docente e Aluno), gerenciamento de vínculos entre entidades (aluno x turma, docente x curso), lançamento de avaliações parciais e organização das unidades curriculares.

Durante o desenvolvimento foram aplicados conceitos de modelagem de banco de dados, relacionamentos utilizando Eloquent ORM (hasMany, belongsTo, belongsToMany), migrations, validações e manipulação estruturada de dados, garantindo integridade e organização das informações.

O projeto tem como foco substituir o sistema interno de gerenciamento escolar do Senac por uma solução digital estruturada, moderna e centralizada, promovendo maior eficiência com foco de automatizar processos facilitando todos os usuários promovendo transparência e melhor acompanhamento da jornada acadêmica.

✨ Funcionalidades:
🔐 Autenticação e Controle de Acesso
O sistema possui autenticação com três perfis distintos: Administrador, Docente e Aluno.
Cada usuário visualiza apenas as funcionalidades permitidas ao seu perfil, com redirecionamento dinâmico após o login e controle de permissões aplicado no backend.

👨‍🎓 Gestão de Alunos
Cadastro, edição e exclusão de alunos
Validação automática de CPF no momento do cadastro
Geração automática de RA (Registro Acadêmico) único
Associação de alunos às turmas
Visualização do próprio desempenho acadêmico
O aluno pode acompanhar suas notas e evolução de forma organizada, com visualização por Unidade Curricular (UC), garantindo maior clareza sobre seu progresso ao longo do curso.

👨‍🏫 Gestão de Docentes
Cadastro e manutenção de docentes
Vinculação de docentes a cursos e unidades curriculares
Lançamento de avaliações parciais
Realização de chamada (controle de presença dos alunos)
Registro de informações pedagógicas
O docente possui acesso às turmas vinculadas, podendo registrar presença e notas, contribuindo diretamente para o acompanhamento acadêmico dos alunos.

📚 Gestão Acadêmica
Cadastro de cursos e turmas
Organização das Unidades Curriculares (UCs)
Estruturação do ciclo acadêmico de forma centralizada

🔄 Sistema de Vínculos
Relacionamento aluno × turma
Relacionamento docente × curso
Implementação de tabelas pivot utilizando Eloquent ORM para gerenciar relacionamentos muitos-para-muitos

📝 Avaliações Parciais
Lançamento de notas pelos docentes
Registro de indicadores de desempenho
Armazenamento estruturado das avaliações no banco de dados
Consulta das notas pelo aluno de acordo com cada Unidade Curricular

🛡️ Integridade e Validação de Dados
Validação de campos obrigatórios
Regras de consistência aplicadas no backend
Utilização de relacionamentos estruturados com Eloquent ORM
Garantia de integridade referencial entre as entidades do sistema

🛠 Tecnologias Utilizadas
PHP 8.x
Laravel 10
Eloquent ORM
SQLite (ambiente de desenvolvimento)
HTML5
CSS3
JavaScript
Bootstrap 5

# Sistema de gestão de banco de sangue

Esse é um sistema de gestão de banco de sangue composto por um conjunto de tabelas que representam doações de sangue, contendo tabelas como: Bancos de sangue, Doadores e doações.

O sistema exige que as tabelas existam e estejam em funcionamento, para isso basta executar o script Python a seguir para criação das tabelas e preenchimento dos dados necessarios:

()

Para executar o sistema basta executar o script Python a seguir:

()

Organização
diagramas: Nesse diretório está o diagrama relacional do sistema.
O sistema possui três entidades: DOADORES, BANCO_DE_SANGUE, DOAÇÕES.
sql: Nesse diretório estão os scripts para criação das tabelas.
tabelas.sql: script responsável pela criação das tabelas, relacionamentos e criação de permissão no esquema LabDatabase.
src: Nesse diretório estão os scripts do sistema.
* [sql](src/sql/): Nesse diretório encontram-se os scripts utilizados para geração dos relatórios a partir da [tabelas.sql]    
* [main.py](src/main.py): Script responsável por ser a interface entre o usuário e os módulos de acesso ao Banco de Dados. Deve ser executado após a criação das tabelas.

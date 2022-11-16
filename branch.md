# branchs
são ramificações do projeto, o qual permite vários desenvolvedores, trabalharem em diferentes funcionalidades, sem bugar a versão estável.

## principais branchs
branch main-> que é a branch principal, ou seja, a brnach estável da aplicação. Versão que é disponibilizada aos clientes.

branch developer -> é branch utilizada pelos testers. Os quais vão testar as novas funcionalidades, correções de bugs, etc.

## outras branchs 
para cada nova funcionalidade ou correção de bugs é criada uma nova branch

### padrões para criar nome de branchs
!IMPORTANTE! Nomes de branchs não tem acentos e nem Ç
para correção de bugs: fix_identificacao_do_bug
exemplo: fix_botao_de_login, fix_cor_do_cabecalho

Para novas funcionalidades:
peat_identificacao_da_nova_funcionalidade
exemplo: feat_interacao_com_google, feat_nova_tela_de_contato

para atualizar  documentação: doc_identificacao_da_alteracao
exemplo: doc_adicionada_nova_imagem
para criação/alteração de tarefas que não interfere no código:
chore_identificacao_da_modificacao
exemplo: chore_atualizado_a_versao_do_banco

## comandos para trabalhar com branchs
### criação de novas branchs
git checkout -b nome_da_nova_branch
exemplo: git checkout -b fix_botao_da_tecla_login
obs: O ideal é sempre criar as branchs a partir da main.

### Listar as branchs existentes
git branch list

### Trocar de branch
git swich nome_da_branch_que_deseja_entrar
Exemplo 01: git switch fix_botao_da_tecla_login
exemplo 02: git switch main

### Excluir uma branch
git branch -D nome_da_branch_que_deseja_excluir
Exemplo: git branch -D fix_botao_da_tecla_login

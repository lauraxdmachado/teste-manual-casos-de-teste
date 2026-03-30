# teste-manual-casos-de-teste
Projeto de testes manuais com cenários de teste e bug report

# Projeto de Testes Manuais
Este é meu primeiro projeto de QA.

## Objetivo
Praticar a criação de cenários de teste e identificação de bugs.

## Funcionalidade testada
Tela de Login

## Cenários de teste

### CT001 - Login com dados válidos
Passos:
1. Inserir email válido
2. Inserir senha válida
3. Clicar em entrar

Resultado esperado:
Usuário deve entrar no sistema
---
### CT002- Login com senha incorreta
Passos:
1. Inserir email válido
2. Inserir senha incorreta
3. Clicar em entrar

Resultado esperado:
Sistema deve exibir mensagem de erro
---
## Bug encontrado
### BUG001 - Erro ao logar com senha correta
Passos:
1. Inserir email correto
2. Inserir senha correta
3. Clicar em entrar

Resultado esperado:
Login realizado com sucesso

Resultado atual:
Sistema apresenta erro

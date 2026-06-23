# teste-manual-casos-de-teste
Projeto de testes manuais com cenários de teste e bug report

# Projeto de Testes Manuais
Este repositório apresenta um projeto de testes manuais desenvolvido durante meus estudos em Quality Assurance (QA), contemplando a criação de cenários de teste, casos de teste e registro de defeitos (Bug report).

## Objetivo
Aplicar conceitos fundamentais de testes de software,incluindo elaboração de casos de teste, execução de testes funcionais e documentação de defeitos encontrados durante a validação da aplicação.

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
### BUG001 - Falha de autenticação com credenciais válidas
Passos:
1. Inserir email correto
2. Inserir senha correta
3. Clicar em entrar

Resultado esperado:
Login realizado com sucesso

Resultado atual:
Ao informar credencias válidas e clicar em "Entrar", o sistema impede o acesso do usuário e exibe uma mensagem de erro indevidamente.

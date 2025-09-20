# README.md – Agente de Testes Unitários Automáticos 📄
## Projeto: Agente IA para geração automática de testes com pytest 🚀

Este projeto documenta a construção de um agente de IA que recebe trechos de código Python e gera automaticamente testes unitários em pytest, usando LangChain e Azure OpenAI.

# Objetivos do Projeto 🎯

Receber trechos de código Python como input.

Gerar arquivos de teste (test_<nome>.py) com:

import pytest na primeira linha

Funções def test_* cobrindo casos de sucesso e falha.

Permitir que os testes gerados rodem diretamente com pytest.

# Tecnologias e Bibliotecas Utilizadas 🛠️

Python 3.10+

LangChain (para criação do agente e fluxo de prompt)

Azure OpenAI (processamento e geração de código de testes)

pytest (framework de testes unitários)

dotenv (gerenciamento de variáveis de ambiente)

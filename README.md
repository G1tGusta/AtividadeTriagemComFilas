# Sobre o Sistema

Projeto em Python realizado no GoogleColab que gerencia filas de atendimento em um hospital por especialidade, organizando pacientes conforme prioridade baseada na cor de urgência e hora de chegada. O sistema simula a agenda médica, prevê tempos de espera e permite a chamada dos pacientes em ordem.

## Funcionalidades

* Cadastro de pacientes com prioridade (Vermelho, Laranja, Amarelo e Azul).
* Filas separadas por especialidades médicas.
* Previsão de início e fim de consultas.
* Cálculo do tempo médio de espera.
* Tratamento de casos de empates e filas vazias.

## Bibliotecas Utilizadas

* Python 3
* Biblioteca `heapq` (filas de prioridade)
* Biblioteca `typing` (tipagem)

## Instalação e execução
1- Clone o repositorio:
```bash
!git clone https://github.com/seu-usuario/triagem-hospitalar.git
%cd triagem-hospitalar
```
2- Execute o código diretamente no Colab copiando e colando ou importando os módulos.

3- Para atualizar o código do repositório no Colab, use:
```bash
!git pull
```


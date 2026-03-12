# Análise de Equidade em Modelo de Detecção de Fraude

Este repositório contém um notebook Colab com uma pipeline experimental desenvolvida para avaliação de equidade (fairness) em modelos de classificação para detecção de fraudes financeiras.

## Sobre o Projeto

O experimento investiga como diferentes conjuntos de features impactam a equidade de modelos treinados em cenários com diferentes níveis de viés de representação em dados sintéticos de transações financeiras.

A análise considera um atributo protegido (Ramo de Atividade) e avalia o comportamento dos modelos ao serem treinados e testados em diferentes combinações de bases.

## Estrutura

- `fairness_fraud_pipeline.ipynb`: Notebook contendo toda a pipeline de experimentação, incluindo carregamento, feature engineering, treinamento e cálculo de métricas de viés.

## Execução

Para executar o notebook, é necessário acesso às 10 bases de dados sintéticas utilizadas no estudo. Os dados não estão incluídos neste repositório.

## Contexto Acadêmico

Trabalho desenvolvido para disciplina optativa de Aprendizagem de Máquina, baseado no estudo *"Ignorance and Prejudice in Software Fairness (ICSE 2021)"*.

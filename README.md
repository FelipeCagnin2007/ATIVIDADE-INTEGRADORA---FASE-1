# Relatório Operacional de Pré-Decolagem

Projeto da **Atividade Integradora - Fase 1**, da FIAP.

**Grupo 24**<br>
**Integrante:** Felipe Cagnin de Lima

## Sobre o projeto

O notebook simula a leitura da telemetria de uma missão espacial. O programa verifica:

- temperatura interna e externa;
- integridade estrutural;
- nível de energia;
- pressão dos tanques;
- módulos críticos.

Se todos os valores estiverem dentro das faixas seguras, o resultado será `PRONTO PARA DECOLAR`. Caso exista alguma anomalia, o resultado será `DECOLAGEM ABORTADA` e o programa mostrará os problemas encontrados.

O notebook também calcula a energia restante após a decolagem, considerando capacidade total, carga atual, consumo e perdas.

## Arquivos

- `relatorio_pre_decolagem.ipynb`: notebook com o código e os resultados.
- `conteudo_relatorio.txt`: texto completo para montar o relatório em Word e exportar em PDF.
- `assets/print_execucao.svg`: print da execução do programa.

## Como executar

### Google Colab

1. Acesse [Google Colab](https://colab.research.google.com/).
2. Clique em **Arquivo > Abrir notebook > GitHub**.
3. Cole o link deste repositório.
4. Abra `relatorio_pre_decolagem.ipynb`.
5. Clique em **Ambiente de execução > Executar tudo**.

### Jupyter Notebook

Com o Jupyter instalado, execute:

```bash
jupyter notebook relatorio_pre_decolagem.ipynb
```

Depois, clique em **Run All**. O código usa apenas recursos nativos do Python.

## Print da execução

![Print da execução](assets/print_execucao.svg)

## Faixas seguras usadas na simulação

| Item | Faixa segura |
|---|---|
| Temperatura interna | 18 °C a 27 °C |
| Temperatura externa | -10 °C a 45 °C |
| Integridade estrutural | 1 |
| Energia | mínimo de 80% |
| Pressão dos tanques | 280 kPa a 320 kPa |
| Módulos críticos | todos funcionando |

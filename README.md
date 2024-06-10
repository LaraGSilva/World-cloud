# Análise de Frequência de Palavras

Este projeto é uma análise simples da frequência de palavras em um texto. Ele lê um arquivo de texto, remove palavras específicas e conta quantas vezes cada palavra aparece no texto filtrado. O resultado é uma lista de palavras ordenadas pela sua frequência em ordem decrescente e uma nuvem de palavras visual.

## Requisitos

- Python 3.x
- Pandas
- Matplotlib
- WordCloud

Você pode instalar os pacotes necessários usando o pip:

```bash
pip install pandas matplotlib wordcloud
```

## Estrutura do Projeto

- `script.py`: Contém o código principal para ler o texto, remover palavras específicas, contar a frequência de palavras e gerar a nuvem de palavras.
- `FALAS - LARA.txt`: Arquivo de texto de exemplo com as falas de Lara.

## Como Usar

1. Coloque seu arquivo de texto (por exemplo, `FALAS - LARA.txt`) na mesma pasta do script.
2. Execute o script `script.py` para gerar a análise de frequência de palavras.

### Passos para Executar:

1. **Ler o arquivo de texto**: O script lê o arquivo de texto usando pandas com a codificação correta.
2. **Concatenar texto**: Todas as linhas de texto do DataFrame são concatenadas em uma única string.
3. **Remover palavras específicas**: Palavras comuns que você deseja excluir são removidas da análise.
4. **Contar a frequência de palavras**: As palavras restantes são contadas e ordenadas por frequência.
5. **Gerar a nuvem de palavras**: Uma nuvem de palavras é gerada para visualizar as palavras mais comuns.

## Resultados
O script gera:
- Uma lista de palavras ordenadas por frequência.
- Uma nuvem de palavras visual para representar as palavras mais comuns no texto.

## Desenvolvimento
Esse projeto de analise de dados de palavras foi desenvolvido por Lara Gonçalves da Silva.

 <div align= "center">
<img width="552" alt="Captura de Tela 2024-06-09 às 21 28 10" src="https://github.com/LaraGSilva/world-cloud/assets/66211552/de9f53ea-4227-47b7-aec8-d44dbb3ae201"></div>

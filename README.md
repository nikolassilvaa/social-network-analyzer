# Social Network Analyzer

Este repositório contém um projeto de análise de redes sociais utilizando conceitos da teoria dos grafos. O objetivo é identificar comunidades, visualizar agrupamentos de usuários e extrair insights sobre a estrutura e dinâmica de uma rede social, com foco especial em dados de conexões do Facebook.

## Funcionalidades

- Carregamento do grafo a partir de um arquivo de arestas (`facebook_combined.txt`)
- Visualização da estrutura geral da rede
- Detecção automática de comunidades com o algoritmo Louvain
- Análise dos principais clusters e seus perfis
- Geração de visualizações diferenciando os grupos por cores

## Tecnologias Utilizadas

- Python 3
- NetworkX
- Matplotlib
- Community (python-louvain)

## Instalação

1. Clone este repositório:

git clone https://github.com/seuusuario/social-network-analyzer.git
cd social-network-analyzer

2. Instale as dependências:
pip install networkx matplotlib python-louvain

3. Certifique-se de que o arquivo `facebook_combined.txt` está no diretório do projeto.

## Como Usar

- Execute o notebook `social-network-analyzer.ipynb` em um ambiente Jupyter.
- Siga as células, que carregam a rede, detectam comunidades e geram os gráficos.
- Explore diferentes clusters e visualize suas conexões.

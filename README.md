# Analise-e-Sugestao-Automatica-de-Respostas
Este projeto tem como objetivo me auxiliar no meu trabalho como analista residente, onde preciso responder chamados ao longo do dia. Para otimizar esse processo, desenvolvi um sistema capaz de identificar chamados semelhantes já resolvidos e sugerir possíveis respostas para novos chamados.

Testei duas abordagens para encontrar similaridade entre chamados:

* KNN com palavras-chave previamente selecionadas.
* TF-IDF para análise baseada em relevância dos termos.

  
Após definir a melhor abordagem, implementei um script em Streamlit para facilitar a inclusão de novas demandas. Isso permite aprimorar continuamente o algoritmo, tornando-o mais robusto e preciso à medida que novos chamados são adicionados.

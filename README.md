# Classificao de imagens de documentos

##Passo-a-passo do que fazer:

1) Baixar o dataset de documentos escaneados e fazer a divisão em treinamento, validação e testes;

2) Treinar redes neurais convolucionais profundas nos dados de teste: AlexNet (sem pré-treinamento).

3) Extrair os caracteres de cada documento (em todos: treinamento, validação e testes) e montar um DataFrame contendo o texto formado a partir dos caracteres extraídos. Sugestões: Pytesseract e PyMuPDF.

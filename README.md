# 🛍️ Sistema de Recomendação de Produtos 💻

## ✨ Descrição do Projeto 

Este projeto utiliza o poder da Inteligência Artificial do Google Gemini para criar um sistema de recomendação de produtos. Com base no histórico de compras de um usuário, o sistema sugere novos produtos que podem ser do seu interesse! 

## 🚀 Tecnologias Utilizadas

* **Pandas:** Para manipulação e análise de dados. :panda_face:
* **Requests:** Para realizar requisições HTTP e obter dados da API. :globe_with_meridians:
* **Google Gemini:** Para gerar embeddings de texto e realizar buscas semânticas. :brain:
* **NumPy:** Para operações matemáticas eficientes em arrays. :abacus:

## ⚙️ Funcionamento do Sistema

1. **Coleta de Dados:** Os dados dos produtos são coletados de uma API (neste caso, https://dummyjson.com/products). :package:
2. **Geração de Embeddings:** O Google Gemini gera embeddings (representações matemáticas de texto) para cada produto, capturando seu significado semântico. :dna:
3. **Histórico do Usuário:** O sistema considera o histórico de produtos que o usuário já comprou. :hourglass_flowing_sand:
4. **Busca Semântica:** Quando o usuário busca por um produto ou precisa de uma sugestão, o sistema gera um embedding para a consulta. Então, compara esse embedding com os embeddings dos produtos, encontrando o mais similar. :mag:
5. **Recomendação:** O produto mais similar, com base na semântica dos produtos x histórico do usuário. :tada:

## 💻 Exemplo de saída

```
{
  "Product": "Microsoft Surface Laptop 4",
  "Description": "Style and speed. Stand out on HD video calls backed by Studio Mics. Capture ideas on the vibrant touchscreen.",
  "Price": 1499,
  "Category": "laptops",
  "Brand": "Microsoft Surface" 
}

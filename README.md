# 🛡️ Análise de Documentos Anti-fraude com Azure AI
<p align="center">
  <img src="docs/images/banner-analise-documentos-azureai.png" width="100%" />
</p>

---

## 📖 Visão Geral

Este projeto demonstra como configurar recursos no **Microsoft Azure** para criar uma solução de **análise de documentos com foco em prevenção de fraude**.  
A configuração inicial é fundamental para que os serviços de inteligência artificial possam processar documentos de forma segura e organizada.  

Cada print fornecido representa uma etapa prática dentro do portal Azure.  
O objetivo é mostrar, passo a passo, como montar a base necessária para que o sistema funcione corretamente.

---

## 🚀 Etapas da Configuração no Azure

### 🔹 Criação do Resource Group
📌 *A imagem será adicionada aqui*  
O **Resource Group** é o primeiro passo da configuração. Ele funciona como uma pasta lógica dentro do Azure, onde todos os recursos relacionados ao projeto ficam agrupados.  
Isso facilita:  
- Organização dos recursos  
- Gerenciamento centralizado  
- Exclusão futura de todos os recursos de uma vez, se necessário  

---

### 🔹 Criação do Storage Account
📌 *A imagem será adicionada aqui*  
O **Storage Account** é o serviço de armazenamento do Azure.  
Aqui serão guardados os documentos que precisam ser analisados (recibos, faturas, contratos, cartões de visita).  

Na configuração, é necessário definir:  
- Nome único para a conta  
- Região de hospedagem  
- Tipo de redundância (para garantir segurança e disponibilidade dos dados)  

Esse recurso é essencial, pois será o repositório principal dos arquivos que passarão pela análise.

---

### 🔹 Criação da Instância Document Intelligence
📌 *A imagem será adicionada aqui*  
O **Document Intelligence** é o serviço que aplica **machine learning** para extrair informações de documentos.  
Nesta etapa, você cria a instância do serviço, definindo:  
- Nome da instância  
- Região de hospedagem  
- Plano de preços (dependendo da escala do projeto)  

Esse recurso será responsável por analisar os documentos enviados e gerar resultados estruturados, como campos extraídos e dados organizados.

---

### 🔹 Organização dos Containers
📌 *A imagem será adicionada aqui*  
Dentro da **Storage Account**, são criados **containers** para organizar os documentos.  
Cada container pode ser usado para um tipo de documento específico, por exemplo:  
- `recibos`  
- `faturas`  
- `contratos`  
- `cartoes`  

Os containers são privados por padrão, garantindo que apenas usuários autorizados possam acessar os arquivos.  
Essa organização é fundamental para manter a segurança e facilitar o processamento dos documentos.

---

## 📸 Prints do Projeto

Os prints representam as principais etapas de configuração do ambiente no Azure:  
- O **Resource Group** centraliza todos os recursos do projeto.  
- O **Storage Account** armazena os documentos que serão analisados.  
- O **Document Intelligence** aplica inteligência artificial para extrair informações.  
- Os **containers** organizam os arquivos de forma segura e estruturada.  

Com essa base configurada, o próximo passo será integrar os serviços de IA para análise e detecção de fraude.

---

## 📜 Licença

Este projeto está licenciado sob a licença MIT.  
Você pode usar, modificar e distribuir livremente, desde que mantenha os créditos ao autor.

---

## 👤 Autor

<div align="center">

<strong>Mateus Ferreira Gomes</strong>

<br>

🔗 <a href="https://github.com/mateus-ferreira-gomes">GitHub</a> • 
💼 <a href="https://linkedin.com/in/mateus-ferreiragomes">LinkedIn</a> • 
📧 mateusgomes064@gmail.com

<br><br>

Feito com carinho e dedicação 💙

</div>

---

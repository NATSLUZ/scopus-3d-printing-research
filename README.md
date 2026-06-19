# Nexus 3D | Intelligence Analytics 🚀

**Nexus 3D** é um dashboard acadêmico de alta performance desenvolvido para organizar, explorar e conectar dados científicos extraídos do Scopus, com foco exclusivo em pesquisas sobre **Impressão 3D**.

A plataforma transforma arquivos CSV brutos em inteligência visual, permitindo identificar tendências, núcleos de coautoria e grupos conceituais através de uma interface moderna e intuitiva.

## 🔗 Acesse o Sistema
O Nexus 3D está disponível online através do GitHub Pages:
👉 **[https://natsluz.github.io/scopus-3d-printing-research/](https://natsluz.github.io/scopus-3d-printing-research/)**

---

## ✨ Funcionalidades Principais

- **Nexus Analytics Pro:** 7 gráficos interativos (Chart.js) que analisam:
  - Produtividade anual (Publicações e Citações).
  - Top 15 Periódicos e Top 20 Autores.
  - Distribuição de Idiomas e Tipos de Acesso (Open Access).
  - Nuvem de Palavras-Chave (Keywords).
- **Mapas de Rede (Vis.js):** 
  - **Mapa de Coautoria:** Visualize as conexões entre pesquisadores.
  - **Mapa de Termos:** Identifique como as tecnologias se relacionam.
  - **Grupo Conceitual (Top 15):** Um mapa estático focado no "core" da pesquisa.
- **Sincronização Relacional:** Importador CSV inteligente que povoa automaticamente 4 tabelas no banco de dados (`artigo`, `autor`, `palavras_chaves` e `referencia`).
- **Explorador de Dados:** Busca em tempo real com painéis de detalhes (Abstracts) justificados e elegantes.
- **Interface Premium:** Design escuro (Sidebar), animações suaves e modo foco para gráficos.

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3 (Modern UI), JavaScript (ES6+).
- **Banco de Dados:** PostgreSQL hospedado via [Supabase](https://supabase.com/).
- **Gráficos:** [Chart.js](https://www.chartjs.org/).
- **Grafos de Rede:** [Vis.js](https://visjs.org/).
- **Processamento de Dados:** [PapaParse](https://www.papaparse.com/) (Parsing de CSV).
- **Ícones:** Font Awesome 6.

## 🚀 Como Utilizar

1. Acesse o [Link do Projeto](https://natsluz.github.io/scopus-3d-printing-research/).
2. No menu lateral, utilize o botão **"IMPORTAR CSV"**.
3. Selecione o arquivo `.csv` exportado do Scopus.
4. Aguarde a tela de **Sincronização Nexus Pro** terminar o processamento.
5. Navegue pelas abas para explorar as descobertas!

## 👤 Desenvolvedor

**Natan Luz**
Estudante de Engenharia de Software na **UNEB** (Universidade do Estado da Bahia).
Desenvolvedor focado em análise de dados, arquitetura relacional e tecnologias que facilitam o acesso ao conhecimento acadêmico.

- 🌐 [GitHub](https://github.com/NATSLUZ)
- 📧 [E-mail](mailto:natanluz.2020@gmail.com)

---
*Nexus 3D - Inteligência Acadêmica ao seu alcance.*

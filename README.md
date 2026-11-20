# 📊 Dashboard de Salários na Área de Dados

Dashboard interativo para explorar salários de profissionais da área de dados ao longo dos anos. Use os filtros na barra lateral para refinar a análise e veja métricas e gráficos se atualizarem na hora.

🔗 **Acesse o app:** [dashboard-imersao.streamlit.app](https://dashboard-imersao.streamlit.app)

![Prévia do dashboard](COLOQUE-AQUI-O-NOME-DA-IMAGEM.png)

## ✨ Funcionalidades

- **Filtros** por ano, senioridade, tipo de contrato e tamanho da empresa.
- **Métricas gerais** (salário anual em USD): salário médio, salário máximo, total de registros e cargo mais frequente.
- **Gráficos interativos**:
  - Top 10 cargos por salário médio
  - Distribuição dos salários anuais
  - Proporção dos tipos de trabalho (remoto, híbrido, presencial)
  - Mapa com o salário médio de cientistas de dados por país
- **Tabela de dados detalhados**, atualizada conforme os filtros.

## 🛠️ Tecnologias

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/): interface web
- [Pandas](https://pandas.pydata.org/): manipulação dos dados
- [Plotly](https://plotly.com/python/): gráficos interativos

## 🚀 Como rodar na sua máquina

1. Clone o repositório:

   ```bash
   git clone https://github.com/Juanbiancardi/dashboard.git
   cd dashboard
   ```

2. (Opcional) Crie e ative um ambiente virtual:

   ```bash
   python -m venv venv
   venv\Scripts\activate        # Windows
   source venv/bin/activate     # Linux/macOS
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Inicie o app:

   ```bash
   streamlit run app.py
   ```

O navegador abre sozinho. Se não abrir, acesse o endereço mostrado no terminal (normalmente `http://localhost:8501`).

## 📁 Estrutura do projeto

```
dashboard/
├── app.py             # código do dashboard
├── requirements.txt   # dependências
└── README.md
```

## 📚 Sobre o projeto

Este projeto foi desenvolvido durante a **Imersão em Python da [Alura](https://www.alura.com.br/)**, como forma de praticar análise e visualização de dados. O código segue a estrutura ensinada na aula, e eu estudei cada parte do funcionamento.

Os dados vêm do repositório [vqrca/dashboard_salarios_dados](https://github.com/vqrca/dashboard_salarios_dados), e o arquivo é lido diretamente de lá.

## 🔭 Próximos passos

- [ ] Corrigir o tratamento quando nenhum filtro está selecionado
- [ ] Adicionar a mediana salarial às métricas
- [ ] Criar um gráfico novo (por exemplo, salário por tamanho da empresa)
- [ ] Guardar uma cópia dos dados no próprio repositório
- [ ] Permitir perguntas em linguagem natural sobre os dados, usando um LLM

## 👤 Autor

**Juan Biancardi**
[GitHub](https://github.com/Juanbiancardi)

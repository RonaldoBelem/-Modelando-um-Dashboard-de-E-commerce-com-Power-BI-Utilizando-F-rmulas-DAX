#  Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX


##  Etapas do Projeto

1. **Criação das Tabelas Dimensão e Fato:**
   - Extraímos colunas específicas da tabela original para compor cada dimensão e tabela fato.
   - Utilizamos **agrupamentos** e **condicionais** para criar novas colunas derivadas.

2. **Tabela de Calendário via DAX:**
   - Geramos a **D_Calendário** utilizando a função `CALENDAR()` para garantir uma tabela de datas completa.

3. **Construção de Colunas Condicionais:**
   - Exemplo: Criamos um **Índice de Produtos** a partir de condições aplicadas sobre os dados.

4. **Reorganização das Colunas:**
   - As colunas foram reordenadas para facilitar a visualização e tornar a análise mais eficiente.

---

##  Funcionalidades e Funções DAX Utilizadas
- **Função CALENDAR()**: Para gerar a dimensão de datas.
- **Agregações**: Média, Mediana, Mínimo e Máximo.
- **Condicionais**: Criação de colunas derivadas com base em regras de negócio.

---

##  Arquivos no Repositório
- **Financials_origem**: Tabela original usada como backup (oculta).
- **Desafio_star_schema.pbix**: Arquivo Power BI com o modelo dimensional criado.
- **starschema.png**: Imagem do esquema em estrela.

![Star Schema](./starschema_02.png)

---

## 🏁 Instruções para Submissão
- Salve o projeto no formato **.pbix**.
- Inclua uma **imagem** do esquema em estrela no repositório.
- **Descreva no README** o processo de construção, as funcionalidades e as funções DAX utilizadas.
- **Compartilhe o link do repositório** no GitHub para facilitar a submissão e mostrar seu trabalho para recrutadores e outros profissionais.

---

##  Finalidade do Projeto
Este projeto demonstra habilidades em:
- **Modelagem dimensional** usando Power BI.
- **Manipulação de dados com DAX** e **Power Query**.
- **Organização e documentação de projetos** para facilitar a colaboração e a visualização de recrutadores.


---

## Tecnologias e Ferramentas Utilizadas
- 🟡 **Power BI**  
- 🧮 **DAX**  
- 🔄 **Power Query**  

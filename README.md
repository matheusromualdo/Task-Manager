# ✅ Gerenciador de Tarefas / Task Manager

Um app simples e elegante feito com [Streamlit](https://streamlit.io/) para organizar suas tarefas do dia a dia.  
Você pode **adicionar**, **atualizar o status** e **remover** tarefas, além de visualizar o progresso em um gráfico interativo.

A simple and elegant [Streamlit](https://streamlit.io/) app to manage your daily tasks.  
You can **add**, **update status**, **remove** tasks, and visualize your progress in an interactive chart.

---

## 🚀 Tecnologias usadas / Technologies Used

- Python 🐍
- Streamlit 📊
- SQLite 🗃️
- Pandas 🐼
- Plotly 🍰

---

## 🛠️ Funcionalidades / Features

- ✅ **Adicionar nova tarefa / Add new task:** campo de texto e botão para adicionar tarefas à lista.  
  A text input and button to add tasks to the list.
- 🔄 **Atualizar status / Update status:** permite alterar entre "Pendente" e "Concluída" com um selectbox.  
  Allows switching between "Pending" and "Completed" using a selectbox.
- ❌ **Excluir tarefa / Delete task:** botão para remover a tarefa da lista e do banco.  
  Button to remove a task from the list and the database.
- 📊 **Gráfico de progresso / Progress chart:** visualização em gráfico de pizza mostrando o status das tarefas.  
  Pie chart showing the status of your tasks.
- 💾 **Persistência com SQLite / SQLite persistence:** todas as tarefas são salvas localmente num banco de dados.  
  All tasks are saved locally using a SQLite database.

---

## 🧰 Requisitos / Requirements

Certifique-se de ter o **Python 3.7+** instalado.  
Make sure you have **Python 3.7+** installed.

---

## 📦 Instalação local / Local Installation

1. Clone o repositório / Clone the repository:
```bash
git clone https://github.com/seu-usuario/seu-repo.git
cd seu-repo
```

2. Crie e ative um ambiente virtual (opcional) / Create and activate a virtual environment (optional):
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

3. Instale as dependências / Install dependencies:
```bash
pip install -r requirements.txt
```

4. Execute o app / Run the app:
```bash
streamlit run app.py
```

O navegador abrirá automaticamente em `http://localhost:8501`.  
Browser will open automatically at `http://localhost:8501`.

---

## 🌍 Deploy online / Online Deployment

Este app pode ser facilmente publicado com o [Streamlit Community Cloud](https://streamlit.io/cloud):  
This app can be easily deployed using [Streamlit Community Cloud](https://streamlit.io/cloud):

1. Suba seu projeto no GitHub / Push your project to GitHub
2. Acesse / Go to [streamlit.io/cloud](https://streamlit.io/cloud)
3. Clique em **"Deploy an app"** / Click **"Deploy an app"**
4. Escolha seu repositório e arquivo `app.py` / Choose your repo and `app.py` file
5. Pronto! Seu app estará online 🎉 / Done! Your app is now online 🎉

---

## 📁 Estrutura do projeto / Project Structure

```
📦 gerenciador-tarefas/
├── app.py               # Código principal do app / Main app code
├── tarefas.db           # Banco de dados SQLite (criado automaticamente) / SQLite database (auto-generated)
├── requirements.txt     # Dependências do projeto / Project dependencies
└── README.md            # Documentação / Documentation
```

---

## 📄 Exemplo de requirements.txt / Example requirements.txt

```
streamlit
pandas
plotly
```

---

## 💡 Créditos / Credits

Desenvolvido por / Developed by [Matheus Romualdo](https://github.com/seu-usuario) 🧠💻

---

## 📝 Licença / License

Este projeto está sob a licença MIT.  
Sinta-se livre para usar, modificar e compartilhar!  
This project is under the MIT License. Feel free to use, modify, and share!


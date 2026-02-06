# 📅 Projeto Agenda Django

Aplicação web de **agenda de contatos** desenvolvida com o framework **Django**, permitindo cadastrar, visualizar, editar e excluir contatos de forma simples e organizada.

Projeto com foco em **estudo e prática de desenvolvimento web com Django**, utilizando CRUD, templates, rotas e ORM.

---

## 🚀 Tecnologias Utilizadas

- Python  
- Django  
- HTML  
- CSS  
- SQLite (banco de dados padrão do Django)

---

## ✨ Funcionalidades

- 📋 Listagem de contatos  
- ➕ Cadastro de novos contatos  
- 🔍 Visualização de detalhes  
- ✏️ Edição de contatos  
- 🗑️ Exclusão de contatos  
- 🧩 Organização em apps Django  

---

## 🗂️ Estrutura do Projeto
```bash
Projeto-Agenda-Django/
├── manage.py
├── project/ # Configurações do projeto
├── contact/ # App principal da agenda
├── base_static/ # Arquivos estáticos (CSS, imagens)
├── base_templates/ # Templates HTML
├── utils/ # Funções auxiliares
├── comandos/ # Scripts de gerenciamento
├── db.sqlite3
└── .gitignore
```

---

## ⚙️ Como Executar o Projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/Ingridxisto/Projeto-Agenda-Django.git
cd Projeto-Agenda-Django
```

### 2️⃣ Crie e ative um ambiente virtual
```bash
python -m venv venv
```
#### Windows
```bash
venv\Scripts\activate
```

#### Linux / macOS
```bash
source venv/bin/activate
```

### 3️⃣ Instale as dependências
```bash
pip install -r requirements.txt
```

### 4️⃣ Aplique as migrações
```bash
python manage.py migrate
```

### 5️⃣ Execute o servidor
```bash
python manage.py runserver
```

### 6️⃣ Acesse no navegador
```bash
http://127.0.0.1:8000/
```

## 📦 Dependências
As dependências do projeto estão listadas no arquivo requirements.txt.

Para instalar todas:
```bash
pip install -r requirements.txt
```

## 🤝 Contribuições
Contribuições são bem-vindas!
Sinta-se à vontade para abrir issues, enviar pull requests ou sugerir melhorias.

## 📄 Licença
Este projeto está sob a licença MIT.
Sinta-se livre para utilizá-lo para fins educacionais.

## ⭐ Autor
Desenvolvido por Ingrid Xisto
Se gostou do projeto, deixe uma ⭐ no repositório!

# Sistema de Gestão de Pacientes - Clínica Vida+
Sistema web desenvolvido em **Python** e **Django** para gestão de rotinas, agendamentos e cadastros da Clínica Vida+.

## Funcionalidades
- **Cadastro de Pacientes:** São inseridos nome, idade e telefone com validações de formulário.
- **Dashboard:** Cálculo automático de:
  - Número total de pacientes cadastrados.
  - Idade média do público atendido.
  - Identificação do paciente mais novo e mais velho.
- **Busca Dinâmica:** Pesquisa rápida por nome do paciente.
- **Gerenciamento:** Listagem organizada e remoção de registros.

---

## Tecnologias Utilizadas

- **Backend:** Python 3.x, Django 5.x
- **Frontend:** HTML5, CSS3, Bootstrap 5, FontAwesome
- **Banco de Dados:** SQLite3 (Ambiente de desenvolvimento)

---

## Como Executar o Projeto Localmente

### Pré-requisitos
* Python 3.10+ instalado
* Git instalado

---

### Passo a Passo

1. **Clonar o repositório:**
```bash
git clone [https://github.com/victorhugoatlas/clinica_gestor](https://github.com/victorhugoatlas/clinica_gestor)
```

2. **Criar e ativar o ambiente virtual (venv):**
* **Windows (PowerShell):**
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

* **Linux / macOS:**
```bash
python3 -m venv venv
source venv/bin/activate
```

3. **Instalar as dependências:**
```bash
pip install -r requirements.txt
```

4. **Aplicar as migrations do banco de dados:**
```bash
python manage.py migrate
```

5. **Iniciar o servidor de desenvolvimento:**
```bash
python manage.py runserver
```

6. **Acessar a aplicação:**
Acesse no seu navegador usando a porta fornecida
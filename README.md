# 🎬 Catálogo de Filmes Assistidos

Um aplicativo web para organizar e acompanhar sua jornada cinematográfica.  
Permite adicionar filmes, registrar notas, marcar como assistidos e visualizar estatísticas gerais — tudo de forma simples e intuitiva.

🔗 **Acesse o projeto publicado:** [movie-watchlist-buddy.lovable.app](https://movie-watchlist-buddy.lovable.app)

---

## 🚀 Tecnologias Utilizadas

- **[Supabase](https://supabase.com/)** → Banco de dados e API backend   
- **[Lovable](https://lovable.app/)** → Integração e deploy do projeto  
- **SQL** → Criação de tabelas, views e funções no banco  
- **GitHub** → Controle de versão e documentação

---

## 🗃️ Estrutura do Banco de Dados

O banco foi criado no **Supabase**, com as seguintes tabelas principais:

### Tabela: `filmes`
| Campo | Tipo | Descrição |
|-------|------|------------|
| `id` | serial (PK) | Identificador único do filme |
| `titulo` | text | Nome do filme |
| `diretor` | text | Nome do diretor |
| `ano` | int | Ano de lançamento |
| `genero` | text | Categoria do filme |
| `nota` | int | Avaliação de 0 a 5 |
| `assistido` | boolean | Define se o filme já foi assistido |

---

## 🧩 Scripts SQL

Os arquivos SQL usados no Supabase estão organizados em:

- `create_tables.sql` → Criação das tabelas do banco  
- `views.sql` → Criação de visões para estatísticas (total, média etc.)  
- `functions.sql` → Funções para manipulação e cálculo de dados

---

## 🧠 Modelo Lógico do Banco de Dados
![Modelo Lógico](https://github.com/user-attachments/assets/c6ce81a0-8c50-4b49-8670-2acf4407b879)


*(Substitua o nome do arquivo acima pela imagem do modelo que você exportar do Supabase.)*

---

## 🖥️ Interface do Usuário

A interface foi construída no **WeWeb**, conectando-se diretamente ao Supabase.  
O usuário pode:

- ➕ Adicionar novos filmes  
- ✏️ Editar informações existentes  
- 🗑️ Excluir filmes  
- ⭐ Atribuir notas  
- ✅ Marcar filmes como assistidos  

### Exemplos de Tela

| Tela Principal | Adicionar Filme |
|----------------|----------------|
|(https://github.com/user-attachments/assets/c944606b-3f16-4b49-a374-61ebc51f709c)
|](https://github.com/user-attachments/assets/aa113d0f-7513-4f5d-b9e4-a56e77f77b9a)
|

---

## 🌍 Deploy

O deploy foi feito através da **Lovable**, com integração direta ao Supabase.  
O site está disponível em:

🔗 [https://movie-watchlist-buddy.lovable.app](https://movie-watchlist-buddy.lovable.app)

---

## 🧾 Como Executar / Visualizar o Projeto

1. Acesse o link do projeto publicado (não é necessário instalar nada).
2. Caso deseje reproduzir localmente:
   - Crie um banco no Supabase com o script `create_tables.sql`.
   - Conecte o banco ao WeWeb.
   - Faça o deploy via Lovable ou WeWeb Publish.

---

## 👨‍💻 Autor

**João Pedro Lima Barbosa**  
📅 Projeto desenvolvido em 2025  
📚 Disciplina: Projeto de Banco de Dados
🏫 Instituição: Centro Universitario Santo Agostinho

---

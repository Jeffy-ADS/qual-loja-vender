
# 💡 Como eu fiz pra editar o arquiv `AluraStoreBr.ipynb` no VSCode Usando o Terminal Python

Trabalhar com arquivos `AluraStoreBr.ipynb` (Jupyter Notebooks) no VSCode te oferece o melhor dos dois mundos: **interatividade dos notebooks** com o **poder e recursos avançados do VSCode**.

---

## ⚙️ Etapas para Configurar Jupyter no VSCode
Baixe a extensão no vscode do Jupyter

### ✅ 1. Crie e ative um ambiente virtual (opcional, mas recomendado)
(Uma observação. O bash e o (terminal python))

```bash
# Criação do ambiente virtual
python -m venv venv

# Ativação no Linux/macOS
source venv/bin/activate

# Ativação no Windows
venv\Scripts\activate
```

---

### ✅ 2. Instale o Jupyter via pip
(Uma observação. Eu não precisei fazer isso, mais caso ocorra com vc, saiba que tambem pode ser feito assim.)

```bash
pip install notebook ipykernel
```

> Isso instala o backend necessário para rodar notebooks `.ipynb` no VSCode.

---

### ✅ 3. Instale a extensão do Jupyter no VSCode

1. Abra o VSCode  
2. Vá até a aba de **Extensões** (ícone de quadrado empilhado na barra lateral)  
3. Pesquise por **Jupyter**  
4. Instale a extensão oficial da Microsoft

---

### ✅ 4. Crie um novo notebook

1. No VSCode, vá em **File > New File**  
2. Salve com o nome `exemplo.ipynb`  
3. A interface de células interativas será habilitada automaticamente

---

### ✅ 5. Escolha o Kernel Python

Se aparecer a mensagem **“Select Kernel”** no topo do VSCode:

- Clique e selecione o ambiente Python que você criou com o `venv`
- Ou selecione o Python instalado no sistema, se não estiver usando venv

---

## ✅ Pronto para Usar!

Agora você pode:

- ▶️ Executar célula por célula com `Shift + Enter`
- 📊 Criar gráficos interativos com bibliotecas como `matplotlib` ou `seaborn`
- ✍️ Escrever anotações com Markdown diretamente no notebook

---

**🚀 Dica extra:**  
Use notebooks para prototipar, explorar dados e testar modelos antes de transformar tudo em scripts `.py`.

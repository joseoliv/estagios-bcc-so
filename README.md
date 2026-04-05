# Como Fazer Upload de Arquivos pelo GitHub Web

Este guia explica como enviar (fazer upload) de arquivos diretamente para este repositório usando a interface web do GitHub, sem precisar instalar o Git no seu computador.

---

## Passo a Passo

### 1. Acesse o Repositório

Abra o navegador e vá até a página principal deste repositório no GitHub:  
`https://github.com/joseoliv/estagios-bcc-so`

---

### 2. Navegue até a Pasta Desejada (opcional)

Se quiser enviar os arquivos para uma pasta específica dentro do repositório, clique no nome da pasta até chegar ao local desejado.

---

### 3. Abra o Menu de Upload

Na página da pasta (ou na raiz do repositório), clique no botão **"Add file"** (Adicionar arquivo) e selecione a opção **"Upload files"** (Enviar arquivos).

![Botão Add file > Upload files](https://docs.github.com/assets/cb-26982/mw-1440/images/help/repository/upload-files-button.webp)

---

### 4. Selecione os Arquivos

Você tem duas opções:

- **Arraste e solte** os arquivos da sua máquina diretamente na área indicada na tela, **ou**
- Clique em **"choose your files"** para abrir o gerenciador de arquivos e selecionar os arquivos manualmente.

> **Dica:** Você pode selecionar múltiplos arquivos de uma vez.

---

### 5. Descreva as Alterações (Commit)

Após selecionar os arquivos, role a página para baixo até a seção **"Commit changes"**:

1. No primeiro campo, escreva uma **mensagem curta** descrevendo o que está sendo enviado.  
   Exemplo: `Adiciona relatório de estágio - Semestre 2024/1`

2. (Opcional) No segundo campo, adicione uma descrição mais detalhada.

3. Certifique-se de que a opção **"Commit directly to the `main` branch"** está selecionada.

---

### 6. Confirme o Upload

Clique no botão **"Commit changes"** (ou **"Propose changes"** se não tiver permissão direta).

Pronto! Seus arquivos serão adicionados ao repositório.

---

## Dicas Importantes

- **Tamanho máximo por arquivo:** 25 MB pelo navegador web. Para arquivos maiores, use o Git no terminal ou o GitHub Desktop.
- **Formatos aceitos:** Qualquer tipo de arquivo (PDF, DOCX, imagens, código-fonte etc.).
- **Permissões:** Você precisa ter acesso de escrita ao repositório (ser colaborador) para fazer o commit diretamente. Caso contrário, o GitHub criará automaticamente um *Pull Request* para revisão.

---

## Referências

- [Documentação oficial do GitHub – Adicionando arquivos a um repositório](https://docs.github.com/pt/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [GitHub Desktop (alternativa gráfica)](https://desktop.github.com/)

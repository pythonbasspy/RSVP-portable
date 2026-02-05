# 📖 Leitor RSVP Mobile (Speed Reader)

Um aplicativo web minimalista e responsivo para Leitura Dinâmica usando o método **RSVP** (Rapid Serial Visual Presentation).

O projeto foi desenvolvido com foco em **Mobile First**, garantindo uma experiência ergonômica, tela cheia e livre de distrações para leitura de livros e documentos em alta velocidade no celular.

## 🚀 Funcionalidades

- **Método RSVP com Ancoragem:** As palavras são apresentadas uma a uma, centralizadas com a "Letra de Ancoragem" (Ponto Ótimo de Reconhecimento) destacada em vermelho para reduzir o movimento ocular.
- **Suporte a Arquivos:** Lê nativamente arquivos `.txt`, `.docx` (Word) e `.pdf`.
- **Controle de Velocidade:** Ajuste preciso entre **300 e 900 WPM** (Palavras por Minuto).
- **Navegação Ergonômica:**
  - Botões posicionados na parte inferior para fácil alcance do polegar.
  - Função **Voltar Inteligente**: Permite retornar 1, 5, 10 ou 25 palavras com um toque.
  - Barra de progresso visual.
- **Design Responsivo:** Layout fluido que utiliza 100% da área útil da tela do dispositivo, ajustando o tamanho da fonte automaticamente.

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3:** Estrutura e estilização responsiva (Flexbox, CSS Variables, Viewport Units).
- **JavaScript (Vanilla):** Lógica do motor de leitura e manipulação do DOM.
- **Bibliotecas Externas (via CDN):**
  - [Mammoth.js](https://github.com/mwilliamson/mammoth.js): Para processamento de arquivos `.docx`.
  - [PDF.js](https://mozilla.github.io/pdf.js/): Para renderização e extração de texto de `.pdf`.

## 📱 Como Usar

### Opção 1: Rodar Localmente
1. Clone este repositório ou baixe o arquivo `.html`.
2. Abra o arquivo `index.html` (ou o nome que você definiu) em qualquer navegador moderno (Chrome, Firefox, Safari, Edge).

### Opção 2: Hospedar (Recomendado para Celular)
Para usar como um "App" no celular e evitar bloqueios de segurança de arquivos locais:

1. Vá em **Settings** > **Pages** no seu repositório do GitHub.
2. Em "Source", selecione a branch `main` e salve.
3. O GitHub vai gerar um link (ex: `https://seu-usuario.github.io/seu-repositorio`).
4. Abra esse link no celular e selecione "Adicionar à Tela Inicial".

## 🎮 Controles

| Botão | Ação |
| :--- | :--- |
| **📂 Abrir** | Seleciona um documento do dispositivo. |
| **Slider** | Ajusta a velocidade (WPM). |
| **▶ INICIAR** | Começa ou Pausa a leitura. |
| **⟲** | Volta a quantidade de palavras selecionada no menu ao lado (1, 5, 10, 25). |

## 🤝 Contribuição

Sinta-se à vontade para fazer um fork deste projeto e enviar pull requests. Sugestões de melhorias no algoritmo de ancoragem ou novos formatos de arquivo são bem-vindas.

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Você é livre para usar, modificar e distribuir este software, desde que mantenha os créditos originais.

---

Desenvolvido por: ** [pythonbasspy] **
[https://www.linkedin.com/in/elias-rodrigues-de-oliveira-filho-43503123]

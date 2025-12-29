# AluraPlus 🚀

Página estática demonstrativa com foco em HTML semântico, CSS responsivo e práticas de acessibilidade. 🎯

## Descrição 📝
- O projeto é uma página de apresentação (landing) chamada **AluraPlus**, criada como exemplo para portfólio e uso acadêmico. O objetivo é demonstrar boas práticas de front-end: semântica em HTML, organização de CSS, responsividade e atenção à acessibilidade básica.

## Demonstração / Visualização 👀

https://github.com/user-attachments/assets/a2c888e3-7a08-4fa3-b687-8753642c03bf

- [![Deploy GitHub Pages](https://img.shields.io/badge/deploy-github%20pages-brightgreen)](https://caroline-fraga.github.io/AluraPlus/)
- **Visualização local:** abra o arquivo `index.html` no navegador ou rode um servidor local (recomendado para evitar restrições de carregamento de fontes/recursos).

## Como executar localmente ▶️
1. Método rápido (abrir localmente):
	 - Abra o arquivo `index.html` no seu navegador (duplo clique).
2. Método recomendado (servidor local):
	 - Com Python 3 instalado, execute no terminal na pasta do projeto:

```bash
python -m http.server 8000
# Em seguida, acesse http://localhost:8000
```

## Funcionalidades ✨
- Layout responsivo com grid simples para áreas principais.
- Uso de imagens com `loading="lazy"` para melhorar performance inicial.
- Links de ação estilizados (botões) e navegação no rodapé dentro de `<nav>`.
- Acessibilidade básica: link "pular para o conteúdo", estilos de foco visível, atributos `alt` em imagens e `lang="pt-BR"` no documento.

## Tecnologias utilizadas 🛠️
- **HTML5:** marcação semântica (`header`, `main`, `nav`, `footer`, `headings`) e atributos de acessibilidade.
- **CSS3:** variáveis CSS (`:root`), grid para layout, media queries para responsividade e estilos focais acessíveis.
- **Fontes Google (Inter):** tipografia com fallbacks no CSS.
- **Imagens:** conteúdo em `img/`.

## Estrutura de pastas e arquivos 📁
```
AluraPlus/
├─ index.html        # Arquivo principal com marcação semântica
├─ styles.css        # Estilos globais, variáveis e media queries
├─ README.md         # Este arquivo
└─ img/              # Imagens usadas no projeto (assets)
```

- `index.html`: contém a estrutura da página. Principais seções: header (banner), main (conteúdo), seção de dispositivos e footer.
- `styles.css`: contém variáveis CSS, reset básico, regras de layout e media queries.
- `img/`: ícones e imagens ilustrativas. Recomenda-se manter versões otimizadas.

## Boas práticas aplicadas ✅
- **HTML semântico:** facilita leitura por máquinas, SEO e navegação por leitores de tela.
- **CSS organizado:** uso de variáveis, regras reutilizáveis e media queries para diferentes larguras.
- **Acessibilidade:** link para pular conteúdo, foco visível, atributos `alt`, linguagem do documento e nav com `aria-label`.
- **Responsividade:** grid que adapta de duas colunas para uma em telas pequenas; imagens com `max-width` para evitar overflow.

## Responsividade e acessibilidade (detalhes) 📱♿️
- **Comportamento em dispositivos:** o layout usa `grid` com `grid-template-columns: repeat(2, 1fr)` em telas largas e colapsa para uma coluna em telas < 768px. Títulos e imagens ajustam-se com media queries.
- **Acessibilidade básica implementada:**
	- `lang="pt-BR"` para leitores de tela.
	- Link **Pular para o conteúdo** para navegação por teclado.
	- Estilos de foco visíveis para elementos interativos (botões e links).
	- Texto alternativo (`alt`) para imagens.

## Aprendizados e desafios 🎓
- **Aprendizados principais:**
	- Como aplicar HTML semântico para melhorar acessibilidade e SEO.
	- Organização de CSS com variáveis e como escrever media queries para comportamento previsível.
- **Desafios enfrentados:**
	- Garantir que o layout ficasse estável em diferentes larguras sem quebrar imagens; solução: `max-width` nas imagens e ajustes de padding/margem via media queries.

## Autoria ✍️
Desenvolvido por **Caroline Fraga da Silva**. Projetado para apresentação em portfólio e uso acadêmico.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caroline-fraga-da-silva/)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Caroline-Fraga)

---




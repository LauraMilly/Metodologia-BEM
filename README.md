# Metodologia BEM com SASS

Este projeto tem como objetivo aplicar boas práticas de organização de CSS utilizando a **Metodologia BEM** aliada ao pré-processador **SASS**.

## 📁 Estrutura de Pastas

Metodologia-BEM/
│
├── index.html # HTML com classes no padrão BEM
├── BEM/
│ ├── main.css # CSS compilado a partir do SASS
│ └── sass/
│ ├── main.sass # Arquivo principal que importa os blocos
│ └── produto/
│ └── _produto.sass # Estilos do bloco 'produto' com BEM

markdown
Copiar
Editar

## 🧩 Tecnologias Utilizadas

- HTML5
- CSS3
- SASS (sintaxe `.sass`)
- Metodologia BEM

## 🚀 Como compilar o SASS

Certifique-se de ter o SASS instalado globalmente. Para compilar o projeto, utilize o comando:

```bash
sass BEM/sass/main.sass BEM/main.css

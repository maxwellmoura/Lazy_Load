# Lazy Loading - Projeto Web

Este projeto implementa a técnica de Lazy Loading para otimizar o carregamento de imagens em uma página web. As imagens são carregadas em baixa resolução inicialmente e, conforme o usuário rola a página, a resolução é aumentada dinamicamente.

## 🎯 Funcionalidades

- Carregamento Preguiçoso de Imagens:
- As imagens são carregadas inicialmente em baixa resolução para melhorar a performance.
- Quando a imagem entra na área visível do usuário, sua resolução é aumentada dinamicamente.
# Observador de Interseção:
- Utiliza a API IntersectionObserver para detectar quando uma imagem entra na tela e substitui-la por uma versão de maior qualidade.

# 🛠️ Tecnologias Utilizadas

- **HTML**: Estrutura da página web.

- **CSS**: Estilos responsivos para a página e elementos.

- **JavaScript**: Implementação da lógica de Lazy Loading.

## 📁 Estrutura do Projeto

.
├── css/
│   └── styles.css     # Arquivo de estilos
├── img/               # Diretório para imagens
├── js/
│   └── script.js      # Script de Lazy Loading
└── index.html         # Arquivo principal

##🔧 Funcionalidades de JavaScript

- Interseção com a Tela:
- O script monitora se a imagem entrou na área visível do usuário.
**Substituição da Imagem**:

- Quando a imagem está visível, seu src é atualizado para uma versão de alta qualidade.

##🚀 Como Usar

Abra o arquivo index.html no navegador.
Role a página e observe que as imagens carregam inicialmente em baixa qualidade.
Quando as imagens entram na tela, a resolução é automaticamente ajustada.

## 📱 Responsividade

O layout da página foi desenvolvido para ser responsivo, se adaptando a diferentes tamanhos de tela. Em dispositivos móveis

## 📧 Autor

**Desenvolvido por**: Maxwell Moura  
**LinkedIn**: [Acesse aqui](https://www.linkedin.com/in/maxwell-moura-80a33a6b/)
Agradecemos por conferir este projeto! 🚀

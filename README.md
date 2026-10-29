# Login Responsivo

Projeto de uma tela de login responsiva desenvolvido com HTML5 e CSS3 durante meus estudos por meio das aulas do canal [Curso em Vídeo](https://www.youtube.com/@CursoemVideo), do professor Gustavo Guanabara.

O objetivo do projeto é praticar os conceitos de desenvolvimento web, com foco na criação de interfaces responsivas utilizando Media Queries para adaptar o layout a diferentes tamanhos de tela.

## Sobre o Projeto

A página apresenta uma interface de login com campos para e-mail e senha, botão de acesso e opção para recuperação de senha.

O layout utiliza uma combinação de cores em verde e lilás, ícones e uma imagem de fundo para compor a interface. O design foi desenvolvido para se adaptar a diferentes dispositivos, como celulares, tablets e computadores.

## Funcionalidades

- Layout responsivo para diferentes tamanhos de tela.
- Campo para preenchimento de e-mail.
- Campo para preenchimento de senha.
- Validação básica dos campos pelo navegador.
- Limitação de caracteres nos campos de entrada.
- Botão para acessar a conta.
- Link para recuperação de senha.
- Ícones utilizando Material Symbols.
- Estilização com CSS3 e variáveis para definição de cores.

## Tecnologias Utilizadas

- HTML5
- CSS3
- Media Queries
- Google Fonts Material Symbols

## Responsividade

O projeto utiliza Media Queries para adaptar a interface conforme a largura da tela.

As configurações de responsividade incluem:

- **Dispositivos móveis:** layout vertical, com a imagem posicionada acima do formulário.
- **Tablets:** layout horizontal, com a imagem ocupando 30% da largura e o formulário ocupando 70%.
- **Desktops:** layout horizontal, com a imagem e o formulário ocupando 50% da largura cada.

Os principais pontos de interrupção utilizados no CSS são 768px e 992px.

## Estrutura do Projeto

```text
login-responsivo/
├── css/
│   ├── style.css
│   └── media-query.css
├── favicon/
│   └── person.ico
├── img/
│   └── pattern.jpg
├── esqueci.html
└── index.html
```

A estrutura acima representa os arquivos utilizados pelo projeto. Os nomes e caminhos devem corresponder aos arquivos existentes no repositório.

## Como Executar

1. Faça o download ou clone este repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador.
4. Redimensione a janela do navegador para observar as adaptações do layout.

Não é necessário instalar dependências para visualizar a interface.

## Conceitos Praticados

Durante o desenvolvimento deste projeto, foram praticados os seguintes conceitos:

- Estruturação de páginas com HTML5.
- Estilização de interfaces com CSS3.
- Utilização de variáveis CSS.
- Criação de layouts responsivos com Media Queries.
- Posicionamento e dimensionamento de elementos.
- Utilização de pseudo-classes para efeitos de interação.
- Implementação de formulários HTML.
- Utilização de ícones em interfaces web.

## Observações

Este projeto foi desenvolvido para fins educacionais, como parte dos meus estudos de HTML5 e CSS3 por meio do canal Curso em Vídeo, do professor Gustavo Guanabara.

A interface possui os campos necessários para uma tela de login, mas a autenticação de usuários ainda depende da implementação de um sistema no lado do servidor.

O formulário utiliza o atributo `action="login.php"`, portanto, o processamento das informações dependerá da existência desse arquivo e da implementação da lógica de autenticação.

A funcionalidade de recuperação de senha também depende da implementação correspondente.

## Autor

**David Martins**

- GitHub: [DavidMartins22](https://github.com/DavidMartins22)
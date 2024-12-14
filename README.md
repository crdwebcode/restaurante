# Projeto Nostalgia Restaurant

Este é um projeto web desenvolvido para o restaurante **Nostalgia Restaurant**. Ele oferece uma interface intuitiva para os usuários navegarem pelo cardápio, realizarem reservas, adicionarem itens ao carrinho e finalizarem compras com integração ao **PagSeguro**.

## Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura básica do site.
- **CSS3**: Estilização e responsividade do layout, incluindo Flexbox e media queries.
- **Bootstrap 3.4.1**: Framework CSS para facilitar o desenvolvimento de componentes responsivos.
- **Font Awesome**: Ícones para navegação e interatividade.
- **JavaScript**: Para manipulação de eventos, interatividade e integração com o carrinho e o PagSeguro.

### Backend
- **Integração PagSeguro**: Implementada para realizar transações financeiras de maneira segura.

## Funcionalidades Principais

### 1. **Página Inicial**
- Exibe a logo do restaurante e oferece uma navegação clara e intuitiva através de um menu responsivo.

### 2. **Sobre Nós**
- Apresenta informações detalhadas sobre o restaurante, sua história e os chefs principais.

### 3. **Cardápio**
- Disponibiliza uma aba interativa com pratos salgados, doces e bebidas.
- Botões para adicionar itens ao carrinho de compras.

### 4. **Carrinho de Compras**
- Visualização de itens adicionados, incluindo nome, descrição, preço e imagem.
- Exibição do valor total da compra.
- Integração com o **PagSeguro** para processamento do pagamento.

### 5. **Reservas**
- Formulário interativo para reservas de mesas, permitindo que o usuário insira nome, e-mail, telefone, data, horário e número de pessoas.
- Envio de mensagens via WhatsApp após submissão do formulário.

### 6. **Contato**
- Formulário para envio de mensagens ao restaurante.
- Integração com Google Maps para localização.

### 7. **Interatividade e Responsividade**
- Botão "Voltar ao Topo" para facilitar a navegação.
- Botão flutuante para chat via **WhatsApp**.
- Layout responsivo para atender diferentes dispositivos.

## Como Rodar o Projeto

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/SEU_USUARIO/NomeDoRepositorio.git
   ```

2. **Abra o Projeto**:
   - Navegue até a pasta do projeto e abra o arquivo `index.html` em seu navegador.

3. **Configuração do PagSeguro**:
   - Adicione suas credenciais do PagSeguro (e-mail e token) no script responsável pela integração no arquivo `cart.html`.

4. **Adicione os Arquivos Estáticos**:
   - Certifique-se de que todas as imagens estão corretamente referenciadas na pasta `img`.

## Estrutura de Arquivos

```
|-- /css
|   |-- style.css
|-- /img
|   |-- logo.png
|   |-- logo.ico
|   |-- menu-item-1.png
|   |-- ...
|-- /js
|   |-- scripts.js
|-- index.html
|-- cart.html
|-- README.md
```

## Melhorias Futuras

- Implementar backend para gerenciar os dados do restaurante.
- Adicionar login e gerenciamento de usuários.
- Expandir os métodos de pagamento disponíveis.

## Licença
Este projeto é livre para uso pessoal e educacional. Para fins comerciais, entre em contato com o desenvolvedor.

## Desenvolvido Por
- **Carlos Rodrigues**
- Contato: [crdwebcode@gmail.com](mailto:crdwebcode@gmail.com)

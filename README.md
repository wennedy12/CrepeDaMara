# 🥞 Crepe da Mara - Cardápio Digital

Um cardápio digital interativo e responsivo para a lanchonete Crepe da Mara, desenvolvido com HTML, CSS (Tailwind) e JavaScript vanilla.

## 🚀 Funcionalidades

- **Interface Responsiva**: Design adaptável para desktop, tablet e mobile
- **Cardápio Interativo**: Visualização clara dos sabores e preços
- **Sistema de Carrinho**: Adicione, remova e ajuste quantidades facilmente
- **Modal de Quantidade**: Selecione a quantidade desejada de cada item
- **Adicionais Personalizáveis**: Opções de milho, tomate ou nenhum adicional
- **Opção Para Viagem**: Configure se o pedido é para consumo local ou viagem
- **Integração WhatsApp**: Envio automático do pedido via WhatsApp
- **Cálculo Automático**: Total do pedido calculado em tempo real

## 🎨 Design

- **Paleta de Cores**: Tons de âmbar e laranja para uma identidade visual acolhedora
- **Tipografia**: Combinação das fontes Inter (moderna) e Pacifico (decorativa)
- **UX/UI**: Interface intuitiva com feedback visual e animações suaves
- **Acessibilidade**: Elementos focáveis e estrutura semântica

## 📱 Sabores Disponíveis

### Clássicos (R$ 13,00)
- Queijo e Presunto
- Queijo e Goiabada  
- Queijo e Chocolate

### Premium (R$ 15,00)
- Queijo e Calabresa
- Queijo e Frango
- Queijo e Carne

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização com Tailwind CSS via CDN
- **JavaScript**: Funcionalidades interativas (ES6+)
- **Google Fonts**: Tipografia personalizada
- **WhatsApp API**: Integração para envio de pedidos

## 🚀 Como Usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/wennedy12/CrepeDaMara.git
   cd CrepeDaMara
   ```

2. **Abra o arquivo**:
   - Abra o `index.html` diretamente no navegador
   - Ou use um servidor local como Live Server (VS Code)

3. **Configure o WhatsApp** (opcional):
   - Edite a variável `whatsappNumber` no JavaScript
   - Formato: "5568999999999" (código do país + DDD + número)

## 📋 Estrutura do Projeto

```
CrepeDaMara/
├── index.html          # Arquivo principal da aplicação
└── README.md          # Documentação do projeto
```

## 🔧 Personalização

### Alterar Número do WhatsApp
```javascript
const whatsappNumber = "5568992481275"; // Substitua pelo seu número
```

### Adicionar Novos Sabores
```html
<div class="menu-card" data-name="Novo Sabor" data-price="16.00">
    <h3 class="font-bold text-lg text-gray-800">Novo Sabor</h3>
    <p class="text-gray-600 flex-grow">Descrição do sabor.</p>
    <div class="w-full flex justify-between items-center pt-2">
        <span class="font-bold text-amber-600 text-lg">R$ 16,00</span>
        <button class="add-to-cart-btn">Adicionar</button>
    </div>
</div>
```

### Modificar Adicionais
Edite a seção de adicionais no HTML para incluir novos itens:
```html
<label class="flex items-center space-x-3 cursor-pointer">
    <input type="checkbox" name="adicional" value="Novo Adicional">
    <span class="text-gray-700">Novo Adicional</span>
</label>
```

## 📱 Demonstração

O cardápio funciona da seguinte forma:

1. **Seleção de Sabores**: Clique em "Adicionar" no sabor desejado
2. **Definir Quantidade**: Use o modal para escolher quantos crepes
3. **Gerenciar Carrinho**: Ajuste quantidades com os botões + e -
4. **Escolher Adicionais**: Marque milho, tomate ou nenhum
5. **Configurar Entrega**: Marque se é para viagem
6. **Finalizar Pedido**: Clique em "Enviar Pedido via WhatsApp"

## 🌟 Características Técnicas

- **Responsivo**: Mobile-first design
- **Performance**: Carregamento rápido com CDN
- **Compatibilidade**: Funciona em todos os navegadores modernos
- **SEO**: Meta tags otimizadas
- **Acessibilidade**: ARIA labels e navegação por teclado

## 📞 Contato

Para dúvidas ou sugestões sobre o projeto:
- WhatsApp: +55 68 99248-1275
- GitHub: [@wennedy12](https://github.com/wennedy12)

## 📄 Licença

Este projeto foi desenvolvido para uso comercial da lanchonete Crepe da Mara.

---


**Desenvolvido com ❤️ para Crepe da Mara**

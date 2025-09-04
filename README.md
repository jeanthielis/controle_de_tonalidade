# 📋 Relatório de Qualidade - PorcelanatoPlus

Este é um aplicativo web mobile para geração de relatórios de qualidade de produtos de porcelanato, com funcionalidade de envio por WhatsApp.

## ✨ Funcionalidades

- **Cadastro de múltiplos produtos** em um único relatório
- **Dois tipos de avaliação**: Letra ou Número
- **Campo de justificativa obrigatória** para avaliações numéricas (mínimo 10 caracteres)
- **Visualização do relatório** gerado com todos os produtos
- **Envio por WhatsApp** com formatação adequada
- **Design responsivo** optimizado para dispositivos móveis
- **Interface em escala de cinzas** com aspecto profissional

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilização com escala de cinzas
- **jQuery** - Manipulação do DOM e interatividade
- **Materialize CSS** - Framework para componentes e design material
- **Material Icons** - Ícones da interface

## 📱 Como Usar

### 1. Preenchimento dos Dados
- Informe o nome do **responsável** pela avaliação
- Adicione um ou mais produtos com:
  - Nome do produto
  - Formato (ex: 60x60 cm)
  - Tipo de avaliação (Letra ou Número)

### 2. Justificativa para Avaliação Numérica
- Se selecionar "Número" como tipo de avaliação:
  - Preencha o campo de justificativa
  - É necessário pelo menos **10 caracteres**

### 3. Geração do Relatório
- Clique em "Gerar Relatório" para visualizar
- O relatório inclui data e hora da geração

### 4. Compartilhamento
- Use o botão "Enviar por WhatsApp" para compartilhar
- O relatório é formatado automaticamente para o WhatsApp

## 🎨 Design

A aplicação utiliza uma **escala de cinzas** com tons variados para criar uma interface sóbria e profissional, adequada para o ambiente empresarial.

## 📦 Estrutura do Projeto

```
porcelanato-relatorio/
├── index.html          # Arquivo principal
├── (recursos embutidos) # CSS e JavaScript inline
└── (dependências CDN)   # Materialize, jQuery e Material Icons
```

## 🔧 Personalização

O aplicativo pode ser facilmente personalizado modificando:

- **Cores**: Ajuste as variáveis CSS na raiz do documento
- **Texto**: Altere labels e mensagens conforme necessário
- **Validações**: Modifique as regras de validação no JavaScript

## 📋 Requisitos

Navegadores modernos com suporte a:
- HTML5
- CSS3
- JavaScript ES6+

## 🌐 Deploy

Para implantar esta aplicação, basta fazer upload do arquivo `index.html` para qualquer servidor web ou serviço de hospedagem.

## 📞 Suporte

Para dúvidas ou problemas com a aplicação, verifique se todas as dependências estão carregando corretamente e se o JavaScript está habilitado no navegador.

## 📄 Licença

Este projeto está disponível para uso conforme necessário.

---

**PorcelanatoPlus** - Sistema de controle de qualidade para produtos de porcelanato.

# Calculadora Pokémon Avançada

Uma ferramenta interativa para calcular e comparar danos de Pokémon, além de analisar o custo-benefício de estrelar seus Pokémon versus comprar novos.

## 📋 Sumário

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Como Usar](#como-usar)
- [Instalação](#instalação)
- [Calculadora de Dano](#calculadora-de-dano)
- [Análise de Custo-Benefício](#análise-de-custo-benefício)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Contribuições](#contribuições)
- [Licença](#licença)

## 🔍 Visão Geral

A Calculadora Pokémon Avançada é uma aplicação web que permite aos jogadores tomar decisões estratégicas sobre suas equipes de Pokémon. Ela oferece duas ferramentas principais:

1. **Comparação de Dano**: Compare o poder de ataque entre dois Pokémon diferentes com base em seu tipo, tier e nível de estrelas.
2. **Análise de Custo-Benefício**: Determine se vale mais a pena estrelar um Pokémon existente ou investir em novos Pokémon, com base no investimento necessário e no ganho de dano.

## ✨ Funcionalidades

- **Interface Dark Mode**: Design moderno e confortável para os olhos
- **Comparação direta**: Visualize a diferença de dano entre dois Pokémon
- **Análise de investimento**: Calcule o retorno sobre investimento (ROI) de estrelar Pokémon
- **Recomendações automáticas**: Receba sugestões claras sobre a melhor estratégia
- **Interface responsiva**: Funciona em dispositivos móveis e desktop
- **Aplicação standalone**: Nenhuma instalação ou servidor necessário

## 🚀 Como Usar

A calculadora possui duas abas principais, cada uma com um propósito específico:

### Calculadora de Dano

Compare o poder de ataque entre dois Pokémon:

1. Selecione o tipo, tier e número de estrelas para cada Pokémon
2. Visualize o dano base, bônus de estrelas e dano final de cada um
3. Compare a diferença absoluta e percentual entre os dois
4. Veja qual Pokémon é superior em termos de dano

### Análise de Custo-Benefício

Determine se vale a pena estrelar seu Pokémon:

1. Configure os detalhes do Pokémon que você deseja estrelar:
   - Tipo e tier
   - Estrelas atuais e alvo
   - Preço de cada Pokémon adicional necessário
2. Configure um Pokémon alternativo para comparação
3. Analise os resultados:
   - Quantidade de Pokémon necessários para estrelar
   - Investimento total
   - Ganho de dano ao estrelar
   - Eficiência (dano ganho por moeda investida)
   - ROI (% de aumento de dano por Pokémon investido)
   - Comparação com a alternativa de comprar outros Pokémon

## 📥 Instalação

### Método 1: Uso Local

1. Baixe o arquivo HTML
2. Abra-o em qualquer navegador moderno
3. Pronto! Não requer servidor ou instalação adicional

### Método 2: Hospedagem Online (Gratuita)

1. Acesse [Netlify Drop](https://app.netlify.com/drop)
2. Arraste o arquivo HTML para a área indicada
3. Em segundos, sua calculadora estará online com um URL personalizado
4. (Opcional) Crie uma conta Netlify para personalizar o URL

## 🧮 Fórmula de Cálculo de Dano

O cálculo de dano é baseado na seguinte fórmula:

```
Dano Final = Dano Base × (1 + (Bônus por Estrela × Número de Estrelas) / 100)
```

Onde:
- **Dano Base**: Determinado pelo tipo e tier do Pokémon
- **Bônus por Estrela**: Percentual de aumento por estrela, que varia conforme o tier
  - Tier 3: 2% por estrela
  - Tier 2: 4% por estrela
  - Tier 1: 6% por estrela
  - Super Rare: 8% por estrela
  - Ultra Rare: 10% por estrela
  - Legendary: 15% por estrela
  - Mythical: 15% por estrela

## 💹 Cálculo do Custo-Benefício

A análise de custo-benefício considera:

- **Requisitos para estrelar**:
  - 1★: 2 Pokémon (1 adicional)
  - 2★: 4 Pokémon (3 adicionais)
  - 3★: 8 Pokémon (7 adicionais)
  - 4★: 16 Pokémon (15 adicionais)
  - 5★: 32 Pokémon (31 adicionais)

- **Métricas calculadas**:
  - **Eficiência**: Dano ganho por moeda investida
  - **ROI**: Percentual de aumento de dano por Pokémon investido
  - **Comparação**: Dano total que poderia ser obtido investindo em Pokémon alternativos

## 🛠️ Tecnologias Utilizadas

- **JavaScript ES6+**: Para a lógica de cálculo
- **HTML5**: Estrutura da aplicação
- **CSS3**: Estilos adicionais

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tiver sugestões para melhorar a calculadora, sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commitar suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Enviar um Pull Request

## 📄 Licença

Este projeto foi feito para uso pessoal e não deve ser comercializado.

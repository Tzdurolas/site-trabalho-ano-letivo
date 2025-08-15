# 🔍 Verificador de Notícias - GitHub Pages

Sistema inteligente para verificação de notícias falsas usando HTML, CSS e JavaScript puro.

## 🌐 Acesso Online

**[🚀 Acesse a ferramenta aqui](https://seuusuario.github.io/verificador-noticias/)**

## ✨ Funcionalidades

- ✅ **Análise de texto** com detecção de padrões suspeitos
- ✅ **Verificação de fontes** confiáveis
- ✅ **Score de credibilidade** (0-100%)
- ✅ **Interface moderna** e responsiva
- ✅ **Funciona offline** após o primeiro carregamento
- ✅ **Sem necessidade de servidor** - roda direto no navegador

## 🛠️ Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Design moderno com gradientes e animações
- **JavaScript ES6+** - Lógica de análise no frontend
- **Font Awesome** - Ícones profissionais
- **GitHub Pages** - Hospedagem gratuita

## 🔍 Como Funciona

### Detecção de Fake News

O sistema analisa:

1. **Padrões Linguísticos Suspeitos:**
   - Palavras como "URGENTE", "BOMBA", "EXCLUSIVO"
   - Frases como "MÍDIA NÃO MOSTRA", "COMPARTILHE ANTES QUE APAGUEM"
   - Uso excessivo de pontuação (!!!)
   - Texto em maiúsculas excessivo

2. **Análise de Fontes:**
   - Verifica se o domínio é de fonte confiável
   - Checa se usa HTTPS
   - Lista de sites confiáveis brasileiros e internacionais

3. **Score de Credibilidade:**
   - Combina todos os fatores
   - Gera pontuação de 0-100%
   - Classifica como: Verdadeira, Neutra ou Falsa

## 📱 Como Usar

1. **Cole o texto** da notícia no campo de texto
2. **Ou insira a URL** da notícia (opcional)
3. **Clique em "Verificar Notícia"**
4. **Veja o resultado** com score e recomendações

### Exemplos de Teste

A ferramenta inclui botões para testar com:
- Notícia suspeita (fake news típica)
- Notícia normal (linguagem neutra)
- URL de fonte confiável
## 🎯 Precisão

### Limitações:
- Análise baseada em padrões, não IA avançada
- Não verifica fatos específicos
- Não acessa conteúdo de URLs (limitação do frontend)
- Focado em padrões de fake news em português

### Recomendações:
- Use como ferramenta auxiliar
- Sempre verifique em múltiplas fontes
- Consulte sites de fact-checking
- Use senso crítico

## 📊 Fontes Confiáveis Incluídas

### Brasileiras:
- G1, Folha, Estadão, UOL
- BBC Brasil, CNN Brasil
- Agência Brasil, Band, R7

### Internacionais:
- BBC, Reuters, Associated Press
- The Guardian, NPR

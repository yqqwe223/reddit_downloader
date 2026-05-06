# Reddit Video Parser Tool 🎬

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-Português-yellow.svg)

## 📋 Visão Geral do Projeto

**Reddit Video Parser Tool** é um utilitário baseado na web projetado para auxiliar educadores, pesquisadores e estudantes individuais na análise técnica de conteúdos de vídeo acessíveis publicamente na plataforma Reddit, para fins de arquivamento e estudo sob os princípios de "uso justo" (Fair Use). Esta ferramenta concentra-se em fornecer suporte técnico limpo e eficiente para cenários não comerciais, como coleta de casos de ensino, pesquisa em mídias sociais, análise de cultura digital e gestão do conhecimento pessoal.

🔗 **Demonstração Online**: [https://twittervideodownloaderx.com/reddit_downloader_po](https://twittervideodownloaderx.com/reddit_downloader_po)

> ⚠️ **Aviso Importante**: Este projeto é desenvolvido exclusivamente para fins de aprendizado técnico e pesquisa. Espera-se que os usuários cumpram as leis de direitos autorais aplicáveis e os termos de serviço das plataformas, respeitem os direitos dos criadores originais e se abstenham de usar esta ferramenta para qualquer atividade que infrinja propriedade intelectual ou viole políticas da plataforma.

---

## ✨ Principais Funcionalidades

- 🔗 **Reconhecimento Inteligente de Links**: Analisa automaticamente links de postagens do Reddit, links diretos de vídeo e outros formatos
- 📥 **Adaptação de Qualidade**: Apresenta opções de resolução disponíveis com base em metadados de origem (sujeito à disponibilidade da plataforma)
- 📱 **Compatibilidade Multi-Dispositivo**: Design responsivo otimizado para navegadores de desktop e mobile
- 🔐 **Design Focado na Privacidade**: Nenhum registro de atividade do usuário armazenado; nenhum conteúdo analisado retido nos servidores
- ⚡ **Leve e Rápido**: Lógica de processamento centrada no cliente minimiza a dependência do servidor para respostas rápidas
- 🔄 **Manutenção Ativa**: Atualizações regulares para se adaptar às mudanças de frontend da plataforma e garantir funcionalidade contínua
- 💬 **Extração de Metadados**: Extração opcional de informações públicas como título da postagem, autor, subreddit (apenas para fins de anotação de pesquisa)

---

## 🚀 Guia de Início Rápido

### Passo 1: Obter o Link do Vídeo
1. Abra o site ou aplicativo do Reddit
2. Localize a **postagem de vídeo disponível publicamente** que deseja analisar
3. Clique em "Compartilhar" → "Copiar link", ou copie diretamente a URL da postagem da barra de endereços do navegador

### Passo 2: Enviar para Análise
1. Navegue até: `https://twittervideodownloaderx.com/reddit_downloader_po`
2. Cole o link copiado no campo de entrada designado
3. Clique no botão "Iniciar Análise"

### Passo 3: Revisar Resultados
1. Aguarde o sistema concluir a análise técnica (geralmente alguns segundos)
2. Examine a visualização dos metadados de vídeo e informações disponíveis
3. Prossiga com as ações subsequentes conforme indicado (apenas para fins de aprendizado pessoal)

---

## 💡 Formatos de Link Suportados

```
✅ Padrões de URL recomendados:
- https://www.reddit.com/r/subreddit/comments/xxxxx/video_title/
- https://old.reddit.com/r/subreddit/comments/xxxxx/
- https://v.redd.it/xxxxxxxxxxx/

❌ Cenários atualmente não suportados:
- Postagens definidas como "apenas usuários convidados" ou excluídas
- Conteúdo restrito que requer autenticação ou login para acesso
- Vídeos protegidos por gerenciamento avançado de direitos digitais (DRM)
- Conteúdo que viola as diretrizes da comunidade do Reddit
```

---

## ⚙️ Arquitetura Técnica

| Componente | Implementação | Descrição |
|-----------|---------------|-------------|
| **Frontend** | HTML5 + CSS3 + Vanilla JS | Sem frameworks para carregamento rápido, alta compatibilidade |
| **Gerenciador de Requisições** | Node.js / Python Backend | Assíncrono não bloqueante, suporte a alta concorrência, operação estável |
| **Analisador de Conteúdo** | Expressões Regulares + Análise DOM + API Reddit | Extrai apenas metadados públicos; sem contorno de criptografia, respeito às autorizações |
| **Camada de Segurança** | HTTPS + Sanitização de Entrada + Limitação de Taxa | Previne abusos, garante estabilidade do serviço, protege privacidade do usuário |
| **Implantação** | Docker + Aceleração CDN | Nós distribuídos globalmente para acesso de baixa latência, escalabilidade elástica |

---

## ⚠️ Declaração de Conformidade e Uso Responsável

Esta ferramenta opera estritamente sob os princípios de **neutralidade técnica** e **uso justo**. Por favor, observe as seguintes diretrizes:

### ✅ Casos de Uso Permitidos
- 📚 Instituições educacionais analisando casos de disseminação em mídias sociais para estudos acadêmicos
- 🔬 Amostragem, anotação e pesquisa cultural de conteúdos de vídeo digitais em projetos de pesquisa
- 🗂️ Pesquisadores individuais organizando materiais de referência para inspiração (com atribuição adequada)
- 🌐 Acesso de aprendizado offline em regiões com conectividade à internet limitada
- 📊 Observação e registro não comerciais de fenômenos culturais digitais

### ❌ Atividades Proibidas
- 🚫 Usar conteúdo analisado para distribuição comercial, redistribuição secundária ou monetização de tráfego
- 🚫 Remover informações do autor original ou marcas d'água e republicar conteúdo como obra original
- 🚫 Raspagem em massa, coleta automatizada de dados ou interrupção das operações do Reddit
- 🚫 Tentar contornar controles de acesso para visualizar conteúdo não público ou restrito
- 🚫 Utilizar para disseminar conteúdo ilegal, que infrinja direitos ou viole diretrizes comunitárias

### 📜 Quadro de Referência Legal
- Lei de Direitos Autorais brasileira (Lei nº 9.610/98), art. 46 (limitações aos direitos autorais)
- Lei Geral de Proteção de Dados (LGPD) para aspectos de privacidade
- Política de Conteúdo e Termos de Serviço da plataforma Reddit
- Princípios judiciais internacionalmente reconhecidos de "uso justo" (Fair Use)

> 📌 **Isenção de Responsabilidade**: Os desenvolvedores não assumem responsabilidade pelo uso indevido desta ferramenta. Ao utilizar este software, você reconhece que leu, compreendeu e concorda em cumprir os termos descritos acima.

---

## 🤝 Como Contribuir

Recebemos com satisfação contribuições da comunidade para ajudar a melhorar este projeto:

```bash
# 1. Faça fork do repositório
# 2. Crie um branch de funcionalidade
git checkout -b feature/melhoria

# 3. Confirme suas alterações
git commit -m "feat: otimização da lógica de reconhecimento de links do Reddit"

# 4. Faça push e abra um Pull Request
git push origin feature/melhoria
```

**Diretrizes de Contribuição**:
- Siga as convenções de estilo de código ESLint / Prettier
- Inclua testes unitários para novas funcionalidades quando aplicável
- Use mensagens de commit claras e descritivas em português ou inglês
- Documente novas funcionalidades tanto em comentários de código quanto em atualizações do README
- Certifique-se de que as submissões passem nas verificações básicas de código antes do envio

---

## 🐛 Relatando Problemas

Encontrou um bug ou tem uma sugestão de melhoria?

1. Verifique primeiro a aba [Issues](../../issues) para evitar duplicatas
2. Ao criar um novo issue, por favor inclua:
   - Nome e versão do navegador
   - Instruções passo a passo para reprodução
   - Comportamento esperado vs. comportamento real
   - Capturas de tela ou logs de erro (se aplicável)
   - Exemplo de link de postagem do Reddit (com informações sensíveis anonimizadas)
3. Nossa equipe revisa as submissões regularmente e responderá o mais breve possível

---

## 📄 Licença

Este projeto é distribuído sob a **Licença MIT**. Você é livre para usar, modificar e distribuir este software, desde que o aviso de direitos autorais original e os termos da licença sejam preservados.

```
MIT License

Copyright (c) 2024 Reddit Video Parser Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Agradecimentos

- Gratidão à comunidade de código aberto por fornecer componentes técnicos robustos e inspiração
- Apreciação aos usuários e pesquisadores acadêmicos que contribuem com valiosos feedbacks
- Reconhecimento aos criadores do Reddit cujo trabalho enriquece o valor do conteúdo da cultura digital

---

> 📬 **Suporte e Contato**: Para consultas sobre colaboração técnica ou perguntas relacionadas à conformidade, por favor envie um ticket via GitHub Issues. Esforçamo-nos para responder prontamente a todas as solicitações legítimas.

*Este projeto não é afiliado, endossado ou patrocinado pelo Reddit Inc. ou por qualquer uma de suas afiliadas. Todas as marcas comerciais, logotipos e nomes de marca são propriedade de seus respectivos titulares. Esta ferramenta fornece apenas suporte técnico de análise e não realiza nenhum armazenamento, distribuição ou reivindicação de propriedade sobre conteúdo de terceiros.*
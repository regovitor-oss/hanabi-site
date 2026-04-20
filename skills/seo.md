# SEO Skill — Automação WhatsApp para Clínicas

## Contexto
Este arquivo orienta o Claude Code a otimizar todo conteúdo do site para SEO,
com foco em clínicas médicas, odontológicas e de estética no Brasil (principalmente Rio de Janeiro).

---

## Palavras-chave principais (usar nos títulos e h1/h2)

- automação de atendimento WhatsApp para clínicas
- chatbot WhatsApp para consultório médico
- atendimento automático WhatsApp clínica
- agendamento automático WhatsApp
- bot WhatsApp para clínica odontológica

## Palavras-chave secundárias (usar no corpo do texto)

- inteligência artificial para clínicas
- IA para atendimento médico
- automatizar WhatsApp consultório
- reduzir tempo de resposta clínica
- recepcionista virtual WhatsApp
- agendamento online clínica Rio de Janeiro
- chatbot médico WhatsApp Brasil

## Palavras-chave de cauda longa (ótimas para blog)

- "como automatizar o WhatsApp da minha clínica"
- "chatbot para clínica médica preço"
- "melhor bot WhatsApp para consultório"
- "como reduzir mensagens manuais no WhatsApp da clínica"
- "agendamento automático WhatsApp clínica Rio de Janeiro"
- "quanto custa automação WhatsApp para clínica"

---

## Regras de SEO on-page (aplicar em toda página)

### Meta tags obrigatórias em cada página
```html
<title>[Palavra-chave principal] — Hanabi Automações</title>
<meta name="description" content="[Benefício claro em até 155 caracteres com palavra-chave]"/>
<meta name="keywords" content="automação whatsapp clínica, chatbot médico, agendamento automático"/>
<link rel="canonical" href="https://seudominio.com.br/[slug-da-pagina]"/>
```

### Open Graph (para compartilhamento no Instagram e WhatsApp)
```html
<meta property="og:title" content="[Título da página]"/>
<meta property="og:description" content="[Descrição curta]"/>
<meta property="og:image" content="https://seudominio.com.br/og-image.jpg"/>
<meta property="og:url" content="https://seudominio.com.br/[slug]"/>
```

### Estrutura de headings
- H1: apenas 1 por página, com palavra-chave principal
- H2: seções principais com variações da palavra-chave
- H3: subtópicos e benefícios específicos

---

## Estrutura de blog recomendada

Criar uma pasta `/blog` com artigos focados nas palavras de cauda longa.
Cada artigo deve ter:

- Mínimo 800 palavras
- H1 com a palavra-chave exata do título
- Introdução respondendo a pergunta em 2-3 parágrafos
- Subtítulos H2 com variações da palavra-chave
- CTA para WhatsApp ao final
- URL amigável: `/blog/como-automatizar-whatsapp-clinica`

### Sugestões de primeiros artigos

1. "Como automatizar o atendimento da sua clínica no WhatsApp em 7 dias"
2. "Chatbot para clínica médica: vale a pena em 2025?"
3. "Quanto tempo sua recepcionista gasta no WhatsApp? (e como resolver)"
4. "Agendamento automático pelo WhatsApp: guia completo para clínicas"

---

## SEO local (Rio de Janeiro)

Incluir em rodapé e na página de contato:
- Cidade e bairros atendidos: Rio de Janeiro, Barra da Tijuca, Botafogo, Ipanema, Centro
- Schema markup LocalBusiness (ver abaixo)

```json
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "Hanabi Automações",
  "description": "Automação de atendimento WhatsApp com IA para clínicas e consultórios",
  "telephone": "+55-21-99084-2282",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Rio de Janeiro",
    "addressRegion": "RJ",
    "addressCountry": "BR"
  }
}
```

---

## Checklist antes de publicar qualquer página

- [ ] Title tag com palavra-chave (máx 60 caracteres)
- [ ] Meta description atraente (máx 155 caracteres)
- [ ] H1 único com palavra-chave principal
- [ ] Imagens com atributo `alt` descritivo
- [ ] URL amigável (sem acentos, sem espaços)
- [ ] Link interno para pelo menos 1 outra página
- [ ] CTA visível acima da dobra
- [ ] Site carrega em menos de 3 segundos
- [ ] Mobile-friendly (testar no Google Mobile Test)

---

## Ferramentas gratuitas para monitorar

- **Google Search Console** — indexação e palavras-chave reais
- **Google Analytics 4** — tráfego e comportamento
- **Ubersuggest** — volume de buscas das palavras-chave
- **PageSpeed Insights** — velocidade do site

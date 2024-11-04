# Guia de Estilo

Este guia de estilo define práticas recomendadas para garantir consistência e clareza na escrita de documentação em Markdown. Siga estas diretrizes ao criar ou editar arquivos .md para este projeto.

## 1. Estrutura Básica

- Cada página deve começar com um título #, que será o título principal da página;
- Use subtítulos em ordem (##, ###, etc.) para organizar o conteúdo de maneira hierárquica;
- Inclua uma breve introdução, bibliografia e histório de versão para cada artefato.

### Exemplo 01

```
# Título da Página

## Introdução

Breve introdução.

## Bibliografia

> <a id="QT1" href="#ref1">1.</a> Nome do Autor. Título do Livro ou Artigo. Ano de Publicação.

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | xx/xx/xxxx  | Descrição | [Autor](https://link) | xx/xx/xxxx  | [Revisor](https://link) |

```

## 2. Listas

- Use listas não ordenadas (- ou *) para itens simples.
- Use listas ordenadas (1., 2., etc.) para instruções sequenciais.
- Mantenha a consistência no uso de - ou * para listas não ordenadas.

### Exemplo 02

```
- Item da lista
  - Subitem da lista
- Outro item da lista

1. Passo um
2. Passo dois
```

## 3. Links

- Use links descritivos em vez de URLs cruas.
- Sempre que possível, adicione links internos para outras partes da documentação.
- Links externos devem ser abertos em uma nova aba, quando possível.

### Exemplo 03

```
Veja a [documentação oficial](https://example.com) para mais detalhes.
```

## 4. Imagens

- Use imagens somente quando necessário para ilustrar um ponto importante.
- Todas as imagens devem ter texto alternativo (alt) descritivo.
- Imagens grandes devem ser redimensionadas para evitar que ocupem muito espaço.

### Exemplo 04

```
![Diagrama do processo](Assets/pastacorrespondente/image.png)
```

## 5. Tabelas

- Use tabelas para organizar informações estruturadas.
- Alinhe as colunas para melhorar a legibilidade do código fonte.
- Evite tabelas muito largas; quebre informações longas em várias linhas se necessário.

### Exemplo 05

| Parâmetro | Descrição              | Tipo   |
|-----------|------------------------|--------|
| `nome`    | Nome do usuário        | String |
| `idade`   | Idade do usuário       | Número |
| `ativo`   | Status de atividade    | Booleano |

## 6. Escrita e Tom

- Mantenha o tom profissional e amigável.
- Use frases curtas e parágrafos concisos.
- Evite jargões técnicos complexos; use linguagem clara e direta.

## 7. Convenções Gerais

Nomes de arquivos: Use letras minúsculas e hifens (-) para separar palavras, por exemplo: guia-instalacao.md.
Palavras-chave: Destaque comandos, nomes de arquivos e variáveis com crase (`), como npm install.
Consistência: Mantenha a mesma terminologia e estilo em toda a documentação.

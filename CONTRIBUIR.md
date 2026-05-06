# 🤝 Guia de Contribuição

Obrigado por querer melhorar a Prompts Library! Aqui estão as diretrizes.

## Como Contribuir

### 1. Adicionar um Novo Prompt

- Crie um arquivo `.md` descritivo na pasta apropriada
- Use o template abaixo
- Inclua exemplos práticos

### Template de Prompt

```markdown
# Nome do Prompt

## 📝 Descrição
Breve explicação do que o prompt faz

## 🎯 Objetivo
Qual problema ele resolve

## 💡 Caso de Uso
Quando usar este prompt

## 📋 Prompt

[Cole aqui o prompt completo]

## ✨ Exemplos

### Exemplo 1
Input: ...
Output: ...

### Exemplo 2
Input: ...
Output: ...

## 🔧 Parâmetros
- `{variável1}`: descrição
- `{variável2}`: descrição

## 📚 Referências
Links para artigos ou documentação relacionada

## ✅ Tags
`#tag1` `#tag2` `#tag3`
```

### 2. Melhorar Documentação

- Corrija typos
- Melhore clareza
- Adicione exemplos
- Inclua referências

### 3. Relatar Problemas

- Descreva claramente o problema
- Inclua exemplos se aplicável
- Sugira solução se possível

## Padrões de Código

### Nomes de Arquivo

```
01-tecnicas/
  - chain-of-thought.md
  - prompt-matrix.md
  - reflection.md

02-frameworks/
  - crewai-setup.md
  - multi-agent-debate.md

03-casos-uso/
  - marketing-copywriter.md
  - pesquisa-cientifica.md
```

### Estrutura de Pastas

```
nova-secao/
├── README.md (índice)
├── prompt-1.md
├── prompt-2.md
└── exemplos/
    ├── exemplo-1.py
    └── exemplo-2.json
```

## Processo de Submissão

1. Fork o repositório
2. Crie uma branch: `git checkout -b feature/novo-prompt`
3. Faça suas alterações
4. Commit: `git commit -m "Add: novo prompt de X"`
5. Push: `git push origin feature/novo-prompt`
6. Abra um Pull Request

## Dicas

- 🎯 Seja específico e prático
- 📚 Inclua referências e créditos
- ✨ Teste o prompt antes de submeter
- 🔍 Revise para clareza e gramática
- 💬 Descreva bem no PR

## Licença

Ao contribuir, você concorda que seu código será licenciado sob MIT License.

---

**Dúvidas?** Abra uma issue! 🚀

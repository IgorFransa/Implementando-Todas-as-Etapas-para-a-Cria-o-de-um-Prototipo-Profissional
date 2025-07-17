# 🤝 Guia de Contribuição - Pizza Express

Obrigado por seu interesse em contribuir com o projeto Pizza Express! Este documento fornece diretrizes para contribuições efetivas.

## 📋 Como Contribuir

### 1. Reportar Bugs
- Use o template de issue para bugs
- Inclua passos para reproduzir o problema
- Adicione screenshots quando relevante
- Especifique o ambiente (iOS/Android, versão)

### 2. Sugerir Melhorias
- Descreva claramente a funcionalidade proposta
- Explique o valor para o usuário
- Considere o impacto no design existente

### 3. Contribuir com Código
- Fork o repositório
- Crie uma branch para sua feature
- Siga os padrões de código estabelecidos
- Escreva testes para novas funcionalidades
- Faça commit com mensagens descritivas

## 🎨 Padrões de Design

### Design System
- Siga rigorosamente o design system estabelecido
- Use apenas cores da paleta oficial
- Mantenha consistência tipográfica
- Respeite os espaçamentos definidos

### Componentes
- Reutilize componentes existentes quando possível
- Documente novos componentes criados
- Mantenha acessibilidade em mente
- Teste em diferentes tamanhos de tela

## 💻 Padrões de Código

### Estrutura de Arquivos
```
src/
├── components/     # Componentes reutilizáveis
├── screens/       # Telas do aplicativo
├── services/      # Serviços e APIs
├── utils/         # Utilitários
├── styles/        # Estilos globais
└── assets/        # Imagens e recursos
```

### Nomenclatura
- **Componentes:** PascalCase (ex: `ProductCard`)
- **Arquivos:** camelCase (ex: `userService.js`)
- **Constantes:** UPPER_SNAKE_CASE (ex: `API_BASE_URL`)
- **Variáveis:** camelCase (ex: `userName`)

### Commits
Use o padrão Conventional Commits:
- `feat:` nova funcionalidade
- `fix:` correção de bug
- `docs:` documentação
- `style:` formatação
- `refactor:` refatoração
- `test:` testes

## 🧪 Testes

### Obrigatórios
- Testes unitários para funções utilitárias
- Testes de componente para UI
- Testes de integração para fluxos críticos

### Ferramentas
- Jest para testes unitários
- React Native Testing Library para componentes
- Detox para testes E2E

## 📱 Compatibilidade

### Dispositivos Suportados
- iOS 12.0+
- Android API 21+
- Tablets (adaptação responsiva)

### Performance
- Tempo de carregamento < 3s
- Animações a 60fps
- Uso eficiente de memória

## 🔍 Code Review

### Checklist
- [ ] Código segue padrões estabelecidos
- [ ] Funcionalidade testada em dispositivos
- [ ] Documentação atualizada
- [ ] Performance verificada
- [ ] Acessibilidade considerada

### Processo
1. Abra Pull Request com descrição detalhada
2. Aguarde review de pelo menos 2 desenvolvedores
3. Implemente feedback recebido
4. Merge após aprovação

## 📞 Comunicação

### Canais
- **Issues:** Para bugs e sugestões
- **Discussions:** Para dúvidas gerais
- **Slack:** Para comunicação rápida da equipe

### Etiqueta
- Seja respeitoso e construtivo
- Forneça contexto suficiente
- Responda em tempo hábil
- Mantenha discussões focadas

## 🚀 Deploy

### Ambientes
- **Development:** Builds automáticos de PRs
- **Staging:** Testes de integração
- **Production:** Releases oficiais

### Processo
1. Merge na branch `develop`
2. Testes automáticos executados
3. Deploy em staging para validação
4. Release para produção após aprovação

## 📄 Licença

Ao contribuir, você concorda que suas contribuições serão licenciadas sob a mesma licença do projeto.

---

**Obrigado por contribuir com o Pizza Express! 🍕**


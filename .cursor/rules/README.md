# Cursor Rules

Este diretório contém todas as regras de desenvolvimento migradas do arquivo `.cursorrules` para a nova estrutura `.cursor/rules`.

## Regras Disponíveis

### Core Rules

- **essential-rules.mdc** - Regras essenciais e fundamentais para todos os projetos
- **development-requirements.mdc** - Requisitos de desenvolvimento para Next.js 14
- **problem-solving.mdc** - Abordagem estruturada para resolução de problemas

### Development Standards

- **rails.mdc** - Padrões específicos para Rails 8
- **view_components.mdc** - Padrões para ViewComponent
- **tailwind-v4.mdc** - Padrões para Tailwind CSS v4
- **auto-format.mdc** - Regras de formatação automática

### Authentication & Security

- **authentication-standards.mdc** - Padrões de autenticação com Supabase
- **api_debugging.mdc** - Padrões para debugging de APIs

### Documentation & Planning

- **memory-management.mdc** - Sistema de gerenciamento de memória
- **task-plan-templates.mdc** - Templates para planos de tarefas
- **feature-documentation.mdc** - Padrões para documentação de features
- **documentation-reference.mdc** - Referências de documentação
- **date-time-management.mdc** - Gerenciamento de data e hora

### Version Control & Git

- **git_commit.mdc** - Padrões para commits Git
- **version-control-integration.mdc** - Integração com controle de versão

### Testing & Quality

- **test_driven_development.mdc** - Desenvolvimento orientado a testes
- **rails_console.mdc** - Interação com console Rails

### Observability & Monitoring

- **observability.mdc** - Padrões de observabilidade
- **log_checking.mdc** - Verificação de logs

### Rule Management

- **cursor_rules_location.mdc** - Localização e convenções de regras
- **rule-extraction.mdc** - Extração de regras
- **rule-acknowledgment.mdc** - Reconhecimento de regras
- **meta-rule-management.mdc** - Gerenciamento meta de regras
- **plan-updates.mdc** - Atualizações de planos

## Migração Completa

Todas as regras do arquivo `.cursorrules` original foram migradas para arquivos individuais `.mdc` seguindo a nova estrutura recomendada. Cada regra agora tem:

- Configuração `<rule>` com metadados
- Padrões de glob específicos
- Tags para categorização
- Estrutura organizada e focada

## Uso

Para usar estas regras em um projeto:

1. Copie as regras necessárias para o diretório `.cursor/rules/` do seu projeto
2. As regras serão automaticamente aplicadas baseadas nos padrões de glob
3. Cada regra pode ser ativada/desativada independentemente

## Manutenção

- Atualize as regras conforme necessário
- Mantenha as tags e padrões de glob atualizados
- Documente mudanças significativas
- Teste as regras em projetos reais 
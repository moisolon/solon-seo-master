# Solon+ SEO MASTER — Google, Bing e IA

Pacote v1.0.0 · Base documental revisada em 05/11/2026.

## Instalação

Extraia `solon-seo-master.zip`. Copie a pasta **solon-seo-master** inteira, preservando `SKILL.md`, `references`, `assets` e `agents`:

| Aplicativo | Somente no projeto | Para todos os projetos do usuário |
| --- | --- | --- |
| Codex | `.agents/skills/solon-seo-master/` | `~/.agents/skills/solon-seo-master/` |
| Claude Code | `.claude/skills/solon-seo-master/` | `~/.claude/skills/solon-seo-master/` |

`~` significa a pasta pessoal do usuário. O `SKILL.md` deve ficar diretamente dentro de `solon-seo-master`, sem uma segunda pasta aninhada de mesmo nome. No Codex deste ambiente, a instalação existente também usa `~/.codex/skills`; essa pasta pode ser usada quando reconhecida pela versão/configuração local. A tabela acima usa os diretórios documentados atualmente. Não mantenha cópias divergentes de mesmo nome em múltiplos locais.

O mesmo conteúdo principal serve aos dois aplicativos. `agents/openai.yaml` fornece apenas a apresentação opcional no Codex; a execução da Skill não depende dele. Abra uma nova sessão se a Skill não aparecer e confirme se o aplicativo reconheceu o nome. Não foi alterada a configuração de nenhum aplicativo nem instalada automaticamente esta Skill.

Fontes de formato e instalação: [OpenAI](https://learn.chatgpt.com/docs/build-skills), [tabela oficial de diretórios](https://developers.openai.com/api/reference/cli) e [Claude Code](https://code.claude.com/docs/en/skills).

## Como usar

No Codex, mencione `$solon-seo-master`. No Claude Code, use `/solon-seo-master` ou peça para usar a Skill pelo nome.

Auditoria com relatório, sem alterar o site:

> Use Solon+ SEO MASTER para auditar completamente https://seu-dominio.example. Entregue o relatório com evidências, severidade e correções sugeridas. Neste trabalho, faça somente diagnóstico. Público: [idioma/mercado].

Auditoria com resolução e publicação:

> Use Solon+ SEO MASTER para auditar e corrigir o SEO de https://seu-dominio.example. Autorizo as correções no site e a criação e publicação de artigos evergreen úteis, incluindo uma seção de artigos se necessária. Use o acesso já conectado, respeite o design existente e valide o resultado publicado. Público: [idioma/mercado]. Entregue o relatório do que foi corrigido, publicado e ficou pendente.

Os endereços acima são exemplos, não destinos de publicação. A Skill usa o idioma solicitado para o relatório e o idioma do público para o conteúdo; não impõe Brasil ou português.

## O que está incluído

- Auditoria base e 15 módulos adicionais, com cobertura e limitações explícitas.
- Search Console, Perfil da Empresa/Maps, Bing e presença em buscas com IA.
- DA da Moz, DR da Ahrefs e Authority Score da Semrush considerados individualmente quando os dados estiverem disponíveis.
- Procedimentos de correção, blog/artigos, publicação evergreen e validação em produção.
- Modelo de relatório, severidades, integração conceitual à revisão de site e plano de monitoramento.

A Skill orienta o agente a operar as ferramentas disponíveis. Não contém credenciais, robô autônomo de rastreamento, assinatura de ferramentas ou acesso universal a CMSs. Publicação requer acesso e autorização; instalar o pacote não publica nem agenda nada. O relatório informa o que ficou sem comprovação. Nenhuma técnica garante ranking, indexação ou citações em IA.

## Testes e limites

Consulte `TESTES-SOLON-SEO-MASTER.md` para os testes realizados e seus limites. O pacote é compatível com a estrutura compartilhada de Agent Skills; isso não equivale a uma execução comprovada dentro de todas as versões do Codex e do Claude Code. O ensaio local não altera sites reais.

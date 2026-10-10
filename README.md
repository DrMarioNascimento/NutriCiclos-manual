# NutriCiclos — manual

Nutrição em cada ciclo da vida. Documentação revisada em 10 de outubro de 2026.

Este repositório contém o [manual em PDF](Manual-NutriCiclos.pdf). O código do sistema é mantido em [NutriCiclosSistemas](https://github.com/DrMarioNascimento/NutriCiclosSistemas). O PDF não foi alterado nesta revisão.

## Onde cada componente fica

| Componente | Responsabilidade |
|---|---|
| [Código do sistema](https://github.com/DrMarioNascimento/NutriCiclosSistemas) | Aplicação e ferramentas de desenvolvimento. |
| [Manual](https://github.com/DrMarioNascimento/NutriCiclos-manual) | PDF com orientação de uso. |
| Aplicação publicada | Ambiente de uso da clínica; confirme o endereço com os titulares. |
| Banco configurado no servidor | Dados operacionais; no código auditado, `DATABASE_URL` seleciona PostgreSQL/Neon. |
| [Site da clínica](https://nutriciclos.com.br) | Comunicação pública da NutriCiclos. |

A presença do código no GitHub não comprova a disponibilidade nem a configuração de uma instalação em produção. O ambiente local não deve ser usado como substituto do banco da clínica. O código contém fallback PGLite quando `DATABASE_URL` não está configurada; esse fallback não comprova persistência, backup ou recuperação em produção.

## Consulta do manual

Abra [Manual-NutriCiclos.pdf](Manual-NutriCiclos.pdf). Instruções de instalação, dependências e execução pertencem ao repositório do sistema; este repositório não contém a aplicação para iniciar localmente.

## Titulares e licença

Mario César Nascimento e Osana Melo · Clínica NutriCiclos · Florianópolis/SC.  
Contato: contato@nutriciclos.com.br.

Todos os direitos reservados. Consulte [LICENSE](LICENSE). Esta revisão preserva as permissões e restrições existentes; não concede autorização comercial adicional.

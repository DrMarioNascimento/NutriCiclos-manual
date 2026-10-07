# NutriCiclos

**Estado em 7 de outubro de 2026.** Este repositório guarda o manual em PDF, não o sistema e não os pacientes. Licença proprietária, todos os direitos reservados a Mario César Nascimento e Osana Melo. Revisão documental desta nota: 7 de outubro de 2026.

Consultório de nutrição. Prontuário, avaliação, dieta, cardápio, exames, documentos e agenda.

Nutrição em cada ciclo da vida.

Versão 5.0 · 2026.

## Para quem é

Para a clínica usar no navegador. Não é uma planilha e não abre com dois cliques num arquivo.

## Onde cada coisa fica

O sistema está no ar.

| Lugar | Função | Endereço |
|---|---|---|
| Código do sistema | Guarda o código. Não guarda pacientes. | https://github.com/osanilda-cell/NutriCiclosSistemas |
| Este repositório | Manual em PDF. | https://github.com/DrMarioNascimento/NutriCiclos-manual |
| Netlify | App publicado, em uso. | https://nutriciclossistema.netlify.app |
| Neon | Banco dos pacientes na internet, ligado ao site e em uso. | https://neon.tech |
| Site da clínica | Página pública da NutriCiclos. | https://nutriciclos.com.br |
| Computador da clínica | Cópia local opcional, só enquanto o servidor de desenvolvimento estiver aberto. | http://localhost:8080 |

Pacientes, avaliações, dietas, exames e agenda ficam no Neon. O GitHub não é o banco.

O manual completo, com as telas e o passo a passo, está neste repositório:

https://github.com/DrMarioNascimento/NutriCiclos-manual/blob/main/Manual-NutriCiclos.pdf

## Abrir no computador

Só é necessário para desenvolvimento. O uso do consultório é pelo app no Netlify.

Na pasta de dentro do repositório do sistema, aquela em que aparecem `package.json` e `src`:

```powershell
cd C:\Users\mario\Documents\NutriCiclosSistemas-main\NutriCiclosSistemas-main
$env:VITE_AUTH_ENABLED="false"
.\node_modules\.bin\vite.cmd dev --host 0.0.0.0 --port 8080
```

Abra http://localhost:8080 e deixe a janela azul aberta.

Antes de fechar a cópia local, exporte um backup em Sistema → Backup. No computador, sem o Neon, os pacientes ficam na memória e somem quando o programa para.

A primeira instalação pede o Node.js (https://nodejs.org, versão LTS), o ZIP do repositório do sistema extraído e, no Windows, a permissão para o npm:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

## Licença

Todos os direitos reservados. O texto completo está no arquivo `LICENSE`.

Copiar, modificar ou distribuir este sistema ou este manual exige autorização prévia por escrito dos titulares. A licença não foi convertida em código aberto nesta revisão.

## Titulares

Mario César Nascimento  
Osana Melo  
Clínica NutriCiclos · Florianópolis/SC  
contato@nutriciclos.com.br

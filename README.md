<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Denis Godoi, Desenvolvedor Full Stack. Python, FastAPI, Next.js, PostgreSQL e Linux." />
</p>

<p align="center">
  <a href="mailto:denisfilhocg@gmail.com">denisfilhocg@gmail.com</a> &nbsp;·&nbsp; Uberlândia, MG
</p>

<img src="./assets/divider.svg" width="100%" alt="" />

### Sobre

Desenvolvo sistemas web de ponta a ponta: API em Python/FastAPI, front-end em Next.js, banco PostgreSQL e o servidor Linux onde tudo roda. Desde 2024 mantenho produtos próprios em fintech, energia solar e hospedagens. Antes disso, estagiei como desenvolvedor full stack em uma startup.

Estudo Ciência da Computação na UNITRI e procuro uma vaga de desenvolvedor para trabalhar em time.

<img src="./assets/divider.svg" width="100%" alt="" />

### Projetos

<p align="center">
  <img src="./assets/card-nextsync.svg" width="49%" alt="NextSync: plataforma de gestão financeira pessoal com IA, em produção." />
  <a href="https://clubedaenergia.online"><img src="./assets/card-clube.svg" width="49%" alt="Clube da Energia: marketplace de energia solar compartilhada." /></a>
</p>
<p align="center">
  <a href="https://welcomestays.com.br"><img src="./assets/card-welcome.svg" width="49%" alt="Welcome Stays: sistemas internos de gestão de hospedagens." /></a>
  <img src="./assets/card-gonfc.svg" width="49%" alt="GoNFC: site, API, painel e app de vendas de placas NFC." />
</p>

<sub>O código desses projetos fica em repositórios privados, porque são sistemas de empresas em operação. Abaixo mostro como duas partes deles funcionam.</sub>

<img src="./assets/divider.svg" width="100%" alt="" />

### Como publico o NextSync

Cada push na branch principal passa pelo GitHub Actions e vai para o servidor por um script de deploy. Depois da publicação, um health check testa a API. Se ela não responder, o script volta sozinho para a versão anterior.

<img src="./assets/pipeline.svg" width="100%" alt="Pipeline: git push, GitHub Actions, deploy na VPS, health check. Se passar, a versão nova vai ao ar; se falhar, rollback automático." />

### Validação de documentos no Clube da Energia

O cliente envia os documentos. O navegador faz as primeiras checagens, a IA analisa e dá um score de confiança, e o que fica abaixo do score mínimo vai para uma fila de revisão manual.

<img src="./assets/validacao.svg" width="100%" alt="Validação em três camadas: pré-validação no navegador, análise por IA com score e revisão humana para score baixo." />

<img src="./assets/divider.svg" width="100%" alt="" />

### Stack

<img src="./assets/stack.svg" width="100%" alt="Stack: React, Next.js, TypeScript, Python, FastAPI, PostgreSQL, Linux, Nginx, Docker, GitHub Actions e mais." />

<img src="./assets/divider.svg" width="100%" alt="" />

<p align="center">
  <sub>Para conversar sobre uma vaga ou um projeto: <a href="mailto:denisfilhocg@gmail.com">denisfilhocg@gmail.com</a></sub>
</p>

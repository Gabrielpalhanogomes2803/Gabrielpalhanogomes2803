# Descrições e topics dos repositórios

Proposta preparada em 26/10/2026. As configurações About/topics NÃO foram aplicadas:
a integração disponível altera arquivos, mas não expõe edição desses metadados.

É possível aplicar manualmente em cada repositório, na engrenagem da seção About,
ou executar os comandos abaixo em máquina com GitHub CLI autenticado.
As ações adicionam os topics listados; não removem topics futuros.

```bash
gh repo edit Gabrielpalhanogomes2803/ai-sre-monitor --description 'Observability and AI-assisted incident triage with Prometheus, Grafana, Loki and FastAPI.' --add-topic 'observability,sre,prometheus,grafana,loki,fastapi,docker'
gh repo edit Gabrielpalhanogomes2803/infra-runbooks --description 'Practical Linux runbooks and an automation roadmap for Windows Server and observability.' --add-topic 'linux,runbook,bash,powershell,infrastructure,observability'
gh repo edit Gabrielpalhanogomes2803/tech-challenge-feature-flags --description 'Feature flag platform with AWS EKS, Terraform, CI/CD, GitOps and observability.' --add-topic 'aws,kubernetes,terraform,argocd,gitops,devsecops,feature-flags'
gh repo edit Gabrielpalhanogomes2803/zabbix-infrastructure --description 'Zabbix monitoring lab with Linux and Windows Agent 2 installation scripts.' --add-topic 'zabbix,monitoring,linux,windows-server,powershell,bash'
gh repo edit Gabrielpalhanogomes2803/aws-devops-three-tier-lab --description 'Manual AWS three-tier lab with private backend, PostgreSQL and segmented networking.' --add-topic 'aws,ec2,vpc,nginx,postgresql,cloud'
gh repo edit Gabrielpalhanogomes2803/tech-challenge-feature-flags-- --description 'Earlier reference version of ToggleMaster; see tech-challenge-feature-flags for the main project.' --add-topic 'feature-flags,microservices,reference'
gh repo edit Gabrielpalhanogomes2803/agenda-python --description 'Educational Python CLI contact manager with JSON and CSV support.' --add-topic 'python,cli,learning'
gh repo edit Gabrielpalhanogomes2803/calculadora --description 'Educational calculator built with Vue 3 and Vite.' --add-topic 'vue,vite,javascript,learning'
gh repo edit Gabrielpalhanogomes2803/agenda-de-contatos---html --description 'Educational contact list built with HTML, CSS and JavaScript.' --add-topic 'html,css,javascript,learning'
gh repo edit Gabrielpalhanogomes2803/Pok-mon-em-Python-com-Tkinter --description 'Educational Python and Tkinter game for object-oriented programming practice.' --add-topic 'python,tkinter,oop,learning'
gh repo edit Gabrielpalhanogomes2803/API-de-pa-ses --description 'Educational country lookup application using Python, Tkinter and RestCountries.' --add-topic 'python,tkinter,api,learning'
gh repo edit Gabrielpalhanogomes2803/Bot-de-Busca-de-Telefones-em-An-ncios --description 'Educational Python web scraping exercise with CSV output.' --add-topic 'python,web-scraping,learning'
gh repo edit Gabrielpalhanogomes2803/Desaparecidos-fron-end --description 'Academic front-end prototype for missing-person information.' --add-topic 'html,css,javascript,academic-project'
gh repo edit Gabrielpalhanogomes2803/bitcoin --description 'Educational Python WebSocket and trading API integration experiment.' --add-topic 'python,websocket,learning'
```

Sugestão de projetos para fixar no perfil: ToggleMaster, AI SRE Monitor,
AWS Three-Tier Lab, Infra Runbooks e Zabbix Infrastructure.
A seleção de pins é uma configuração do perfil, separada dos cards do README.

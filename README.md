# SIGAA Mobile
Aplicativo Integrado ao Sistema Integrado de Gestão de Atividades Acadêmicas (SIGAA)

## Descrição do Projeto
Este é um aplicativo móvel que visa integrar funcionalidades da área do aluno no SIGAA. O objetivo é facilitar o acesso a informações acadêmicas, permitindo uma gestão mais prática e organizada dos dados dos estudantes, além de facilitar a comunicação com os órgãos e entidades acadêmicas.

## Status do Projeto
O projeto está atualmente em desenvolvimento.

## Funcionalidades Principais
- Consulta de disciplinas cursadas
- Acompanhamento de notas e faltas
- Visualização de participantes de disciplinas
- Acesso a arquivos disponibilizados por professores
- Emissão do histórico acadêmico

## Tecnologias Utilizadas
- Flutter (versão: 3.19.4)
- Dart (3.3.2)

## Como Executar o Projeto
1. Verifique a disponibilidade de uma API do SIGAA ou outro mecanismo de integração.
2. Clone este repositório.
3. Abra o projeto no Visual Studio Code ou Android Studio.
4. Crie o arquivo **env.local.json** na raiz do projeto e adicione o seguinte código, informando o IP da sua máquina:
```json
{
    "API_URL":  "http://[número IP da sua máquina]:8080/api/v1/"
}

# Especificação do Projeto

## Perfis de Usuários



<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 01 : Empresa </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Donos ou gestores de micro e pequenas empresas locais, como padarias, lojas de roupas, comércios em geral e prestadores de serviços em cidades do interior ou pequenas cidades regionais.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>
1. Encontrar oportunidades de emprego compatíveis com minhas qualificações reais e próximas de casa;
2. Ter acesso rápido e centralizado a vagas divulgadas na região, sem depender apenas de grupos de WhatsApp, Facebook ou indicações pessoais ("boca a boca");
3. Receber alertas ou notificações de posições adequadas ao meu perfil;
4. Cadastrar meu currículo/perfil de forma simples e intuitiva;
5. Aumentar minhas chances de recolocação local, reduzindo a necessidade de deslocamento para cidades maiores.</td>
</tr>
</tbody>
</table>



<table>
<tbody>
<tr align=center>
<th colspan="2">Perfil 02: Candidato </th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Jovens em busca do primeiro emprego, pessoas desempregadas ou profissionais que desejam uma nova oportunidade, moradores de localidades menores ou cidades regionais, com conhecimento básico de tecnologia (principalmente smartphone).</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>1. Contratar rapidamente atendentes, vendedores ou profissionais qualificados que residam na região;
 2. Divulgar ofertas de trabalho de forma ampla e centralizada, sem depender apenas de indicações pessoais, grupos de WhatsApp ou Facebook;
 3. Encontrar candidatos com perfil adequado (habilidades específicas como atendimento ao cliente, organização ou uso básico de ferramentas digitais);
 4. Reduzir o tempo que as vagas ficam abertas ou preenchidas de forma inadequada;
 5. Acessar um sistema simples e acessível via smartphone ou computador, sem burocracia excessiva.</td>
</tr>
</tbody>
</table>





## Histórias de Usuários


Com base na análise da pesquisa de campo forma identificadas as seguintes histórias de usuários:


|EU COMO... `QUEM`   | QUERO/PRECISO ... `O QUE` |PARA ... `PORQUE`                 |
|--------------------|---------------------------|----------------------------------|
| Empresa            | Oferecer vagas de emprego para minha região.                 | Encontrar colaboradores para a empresa.                              |
| Candidato                | Acessar facilmente vagas de emprego de onde resido.                       | Me recolocar no mercado.                              |
| Candidato               | Procurar vagas na minha especialização.                       | Trabalhar mais próximo de onde resido.                              |
| Empresa                | Oferecer vagas de emprego daquela região.                       | Reduzir custos ao contratar colaboradores de cidades distantes.                              |
| Candidato               | Cadastrar meu currículo preenchendo apenas campos básicos e essenciais (nome, contato e o que sei fazer).      | Evitar desistir do cadastro por causa de formulários longos e complexos.   |
| Empresa                | Filtrar candidatos por “Habilidades Específicas” ou “Bairro/Região”.                       | Encontrar rapidamente alguém que more perto e já domine o básico da fun                              |
| Empresa               | Alterar o status da vaga (Aberta / Em Seleção / Finalizada).                       | Encerrar automaticamente o recebimento de currículos após a vaga estar preenchida.               |
| Candidato                | Receber notificações ou alertas de novas vagas compatíveis com meu perfil via WhatsApp ou celular.             | Evitar entrar no site todos os dias só para verificar se surgiu algo novo.   |
| Candidato               | Ter um aplicativo/web leve e funcional no celular (versão mobile).  | Poder me candidatar mesmo sem ter computador em casa.                              |
| Empresa                | Receber um resumo semanal por e-mail com a quantidade de novos currículos que combinam com minhas vagas abertas.      | Não esquecer de consultar a plataforma e manter o processo seletivo em andamento.         |
| Empresa               | Salvar currículos interessantes em um “Banco de Talentos” próprio, mesmo sem vaga aberta no momento.        | Ter a quem recorrer rapidamente caso um funcionário peça demissão inesperadamente.                              |
| Candidato                | Ter meus dados de contato (WhatsApp/E-mail) visíveis apenas para empresas que eu autorizei ou para as quais me candidatei.       | Evitar que pessoas desconhecidas entrem em contato sem o meu interesse.                              |

## Requisitos do Projeto


### Requisitos Funcionais


|ID    | Descrição do Requisito            | Prioridade |
|-------|---------------------------------|----|
| RF-01 |  A plataforma deve permitir ao usuário cadastrar uma conta. | ALTA   | 
|  RF- 02  |  A plataforma deve permitir ao usuário fazer login com sua conta. | ALTA   |
|  RF- 03  |  A plataforma deve permitir ao usuário empresarial cadastrar vagas de emprego.                    | ALTA   |
|  RF- 04  |  A plataforma deve permitir ao usuário cadastrar-se em vagas de emprego.                    | ALTA   |
|  RF-05  |  A plataforma deve permitir ao usuário criar perfil da empresa ou do candidato. | ALTA   |
|  RF-06  |  A plataforma deve permitir ao usuário visualizar informações sobre as empresas e vagas de emprego.                    | ALTA   |
|  RF-07  |  A plataforma deve possuir filtro de vagas de interesse para o usuário.                    | ALTA   |
|  RF-08  |  A plataforma  deve conter ferramentas de busca em uma barra dentro da interface.                    | ALTA   |
|  RF-09  |  A plataforma deve conter cadastro administrativo.                    | ALTA   |
|  RF-10  |  A plataforma deverá conter filtro de localização para o candidato.                    | MÉDIA   |
|  RF-11  |  A plataforma deve permitir ao candidato visualizar o histórico de vagas para as quais se candidatou.                    | MÉDIA   |
|  RF-12  |  A plataforma deve permitir à empresa alterar o status da vaga (Aberta / Em Seleção / Finalizada) e encerrar automaticamente o recebimento de currículos.                    | ALTA   |

**Prioridade: Alta / Média / Baixa. 

### Requisitos não Funcionais


|ID      | Descrição               |Prioridade |
|--------|-------------------------|----|
| RNF-01 |  A plataforma deve ser compatível com os principais navegadores de internet do mercado: Google Chrome, Opera, Firefox e Microsoft Edge.                    | ALTA   | 
| RNF- 02    |  A plataforma deve ser compatível com diferentes layouts de dispositivos, seja em computador, tablet ou smartphone.                    | ALTA   | 
| RNF-03     |  A plataforma deve ter uma interface responsiva e simplificada para o usuário.                    | ALTA   | 
| RNF-04    |  A plataforma deve conter acessibilidade para o usuário.                    | MÉDIA   | 
| RNF-05    |  A plataforma deve conter bons níveis de contraste de cores.                     | MÉDIA   | 
| RNF-06    |  A plataforma deve conter um tutorial para o novo usuário aprender a utilizar a plataforma.                     | BAIXA   | 

**Prioridade: Alta / Média / Baixa. 


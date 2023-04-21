**Projeto Integrador IV 


**Documento de Requisitos do Sistema ENADE – versão 1.0** 

**Histórico de Alterações** 


|**Data** |**Versão** |**Descrição** |**Autor** |
| - | - | - | - |
|21/04/2023 |1\.0 |Finalidade do sistema / requisitos funcionais / diagrama de casos de uso / requisitos não-funcionais. |Letícia Freitas |


**1. Introdução** 

Este documento especifica os requisitos do sistema *ENADE*, através  de casos de uso, fornecendo aos desenvolvedores e clientes as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema. 

1. **Visão geral do documento** 

Além  desta seção introdutória, as seções seguintes estão organizadas como descrito abaixo. 

Seção 2 – **Descrição geral do sistema**: apresenta uma visão geral do sistema abordado,  caracterizando  seu  escopo,  descrevendo  usuários  e  suas  respectivas finalidades. 

Seção 3 – **Requisitos funcionais (casos de uso)**: especifica todos os casos de uso do sistema, descrevendo fluxo de eventos, prioridades, atores, entradas e saídas de cada caso de uso a ser implementado. 

Seção  4  –  **Requisitos  não-funcionais**:  especifica  todos  os  requisitos não-funcionais do sistema, divididos em requisitos de usabilidade, confiabilidade, desempenho, segurança, distribuição, adequação a padrões e requisitos de hardware e software. 

2. **Identificação dos requisitos** 

Ao analisar características a serem atendidas pelo sistema, em cada subseção será definido as expectativas e necessidades do cliente. A referência a requisitos é feita seguido do identificador do requisito, de acordo com a especificação a seguir: 

[Nome da subseção. Identificador do requisito] 

**1.2.1 Prioridades dos requisitos** 

Para estabelecer a prioridade dos requisitos, foram adotadas as denominações “essencial”, “importante” e “desejável”. 

1. **Essencial** é o requisito sem o qual o sistema não entra em funcionamento. Requisitos essenciais são requisitos imprescindíveis, que têm que ser implementados impreterivelmente. 
1. **Importante** é o requisito sem o qual o sistema entra em funcionamento, mas de forma não satisfatória. Requisitos importantes devem ser implementados, mas, se não forem, o sistema poderá ser implantado e usado mesmo assim. 
1. **Desejável** é requisito em que o sistema pode funcionar de forma satisfatória sem ele. Requisitos desejáveis podem ser deixados para versões posteriores do sistema, caso não haja tempo hábil para implementá-los na versão que está sendo especificada. 
2. **Descrição geral do sistema** 

**2.1  Abrangência e sistemas relacionados** 

O exame nacional de desempenho dos estudantes (ENADE) é um dos métodos utilizados para avaliar o desempenho das faculdades e das universidades no País. O principal objetivo é medir a qualidade do ensino superior e contribuir para que as instituições formem alunos com mais habilidades para o mercado de trabalho. 

Visando mapear e avaliar o desempenho dos estudantes diante deste exame, o sistema do ENADE será uma ferramenta na qual disponibilizará dados de provas anteriores, a fim de auxiliar na análise de dados. 

O usuário terá acesso para consulta aos dados de forma intuitiva, e de fácil acesso através de uma interface web. 

3. **Requisitos funcionais (casos de uso)** 
1. **Cadastro** 

**Descrição do caso de uso:** Este caso de uso permite que o usuário realize seu cadastro a fim de utilizar funcionalidades do mesmo. 

Ator: Usuário 

**Prioridade**:  ■ Essencial  Importante  Desejável 

**Entradas e pré-condições**: Nenhuma. 

**Saídas e pós-condição**: Perfil disponível para acesso ao sistema. 


**Descrição do caso de uso:** Este caso de uso permite que o usuário realize seu login, e assim, tenha acesso a interface do sistema. 

Ator: Usuário 

**Prioridade**:  ■ Essencial  Importante  Desejável 

**Entradas e pré-condições**: Possuir cadastro. 

**Saídas e pós-condição**: Perfil disponível para acesso a interface do sistema. 

**Descrição do caso de uso:** Este caso de uso permite que o usuário visualize o seu perfil, e altere seus dados caso seja necessário. 

Ator: Usuário 

**Prioridade**:  ■ Essencial  Importante  Desejável 

**Entradas e pré-condições**: Possuir cadastro. 

**Saídas e pós-condição**:Visualizar e alterar dados pessoais. 

2. **Interface** 

**Descrição do caso de uso:** Este caso de uso permite que o usuário visualize os dados que estão disponíveis no sistema. 

**Prioridade**:  ■ Essencial  Importante  Desejável 

**Entradas e pré-condições**: Possuir cadastro. 

**Saídas e pós-condição**:Visualizar os dados disponíveis. 

**Descrição do caso de uso:** Este caso de uso permite que o usuário baixe os dados que deseja. 

**Prioridade**:  ■ Essencial  Importante  Desejável 

**Entradas e pré-condições**: Possuir cadastro. 

**Saídas e pós-condição**: Baixar os dados disponíveis no sistema. 


**Descrição do caso de uso:** Este caso de uso permite que o usuário pesquise os dados que deseja. 

**Prioridade**:  Essencial  ■ Importante  Desejável 

**Entradas e pré-condições**: Possuir cadastro. 

**Saídas e pós-condição**: Pesquisar os dados disponíveis. 

4. **Requisitos não-funcionais** 

Usabilidade Portabilidade Desempenho 

A  interface  com  o  usuário  é  de  vital  importância  para  o  sucesso  do  sistema. Principalmente por ser um sistema que não será utilizado diariamente, o usuário não possui tempo disponível para aprender como utilizar o sistema. 

**Prioridade**:        ■ Essencial  Importante  Desejável Embora não seja um requisito essencial ao sistema, deve ser considerada por corresponder a um fator de qualidade de software. 

**Prioridade**:  Essencial  ■ Importante  Desejável 


Visando criar um produto com maior extensibilidade, reusabilidade e flexibilidade, deve-se adotar como linguagem principal de desenvolvimento Java seguindo cuidadosamente as técnicas de orientação a objetos. Entretanto, outras linguagens também poderão ser usadas quando indicações técnicas recomendem. O uso da linguagem Java permite não especificar qual será o sistema operacional e a máquina em que o programa irá executar. No entanto, essa máquina deverá se comunicar com um sistema de banco de dados. 

**Prioridade**:  Essencial  ■ Importante  Desejável 

5. **Referências** 
- [https://faro.edu.br/blog/como-funciona-a-nota-no-enade-e-para-que-ela-s](https://faro.edu.br/blog/como-funciona-a-nota-no-enade-e-para-que-ela-serve/) [erve/](https://faro.edu.br/blog/como-funciona-a-nota-no-enade-e-para-que-ela-serve/) 
- <https://www.edrawmax.com/> - diagrama de casos de uso 

# miniguia-da-renda-fixa



🔖 **SUMÁRIO**

    1. Objetivo
    2. Fontes
    3. Testes com a IA
    4. Considerações finais

---

1. 🎯​ **OBJETIVO**

    Aprender sobre investimentos e finanças nunca é uma tarefa fácil no começo. Juros, rendimento, tipos de investimento, taxas e muitos outros assuntos para estudar, e no fim surge a pergunta: "Por onde eu começo?". Por isso, este projeto foi criado com o intuito de guiar o investidor iniciante a dar seus primeiros passos pela base, a renda fixa.
A IA do miniguia, criado no Google NotebookLM, foi treinada com diversas fontes conhecidas do meio financeiro, como o canal do Youtube "Primo Pobre" e blogs como "InfoMoney", além das informações que os próprios bancos, como XP e Santander, disponibilizam.

---

2. ​🖇️​ **FONTES**

    A princípio, foram utilizados apenas 7 fontes:

       . https://www.youtube.com/watch?v=iQFmtW3zlmQ&t=661s
       . https://www.youtube.com/watch?v=Ofd6goeBFho
       . https://www.youtube.com/watch?v=1AaSqjV-29I
       . https://www.youtube.com/watch?v=Q6x0xnI0uCg&t=1s
       . https://investidor10.com.br/renda-fixa/
       . https://www.infomoney.com.br/guias/renda-fixa/
       . https://cmcapital.com.br/blog/renda-fixa-tudo-sobre/

    Em seguida, para complementar o restante, foi feito um Deep Research com o prompt _Pesquise fontes que falam sobre renda fixa e investimentos, como Tesouro Direto, CDB, LCI, LCA..._, gerando assim os seguintes links:

       . https://harioncamargo.com/pdf/apostila_investimentos_porHarionCamargo.pdf
       . https://fastcompanybrasil.com/money/b3-revela-como-comecar-a-investir-com-apenas-r-10-e-fazer-o-dinheiro-render/
       . https://comoinvestir.anbima.com.br/noticia/batalha-de-investimentos-cdb-x-titulos-publicos-2/
       . https://comoinvestir.anbima.com.br/wp-content/uploads/2017/08/13.pdf
       . https://www.bcb.gov.br/detalhenoticia/20686/nota
       . https://conteudos.xpi.com.br/renda-fixa/relatorios/cmn-altera-regras-para-titulos-de-renda-fixa/
       . https://www.genialinvestimentos.com.br/artigos/como-comecar-investir-para-iniciantes/
       . https://investidor10.com.br/iniciante/
       . https://www.genialinvestimentos.com.br/artigos/como-investir-em-renda-fixa/
       . https://www.santander.com.br/blog/educacao-financeira/tesouro-educa-mais
       . https://grafeno.digital/blog/diferenca-entre-lci-e-lca/
       . https://comoinvestir.anbima.com.br/noticia/entenda-o-que-sao-investimentos-prefixados-pos-fixados-e-hibridos/
       . https://www.bicharalaw.com.br/noticias/informativo-extraordinario-cmn-ajusta-lastros-elegiveis-e-prazos-de-vencimento-dos-titulos-incentivados
       . https://comoinvestir.anbima.com.br/noticia/investimento-em-cdb-saiba-como-funciona/
       . https://vmbinvest.com.br/investimento-isento-de-imposto-de-renda/
       . https://comoinvestir.anbima.com.br/noticia/investimentos-de-baixo-risco-aprenda-como-eles-funcionam/
       . https://comoinvestir.anbima.com.br/noticia/investir-ou-pagar-dividas/
       . https://comoinvestir.anbima.com.br/noticia/lci-e-lca-quem-sao-elas/
       . https://conteudos.xpi.com.br/renda-fixa/relatorios/cmn-traz-mais-mudancas-para-a-renda-fixa-o-que-muda/
       . https://www.superrico.com.br/Artigo/lcis-e-lcas-vao-ser-tributadas-e-ainda-assim-vao-valer-a-pena
       . https://www.fgc.org.br/documents/d/guest/material-para-corretoras_versao-dezembro2025
       . https://minhaseconomias.com.br/blog/comece-a-investir/blog-educacao-financeira-o-que-e-o-tesouro-direto-e-como-investir-nele
       . https://www.gov.br/cvm/pt-br/acesso-a-informacao-cvm/perguntas-frequentes-da-cvm
       . https://recargapay.com.br/investimentos-cdb/melhor-investimento-iniciantes
       . https://tozzinifreire.com.br/wp-content/uploads/2026/09/boletim-securitizacao-ed12024.pdf
       . https://www.serasa.com.br/blog/tesouro-educa/
       . https://meubolsoemdia.com.br/Materias/tesouro-educa-mais
       . https://www.nordinvestimentos.com.br/blog/tesouro-renda-mais/
       . https://veja.abril.com.br/economia/tesouro-reserva-veja-o-que-e-e-como-investir-no-titulo-de-renda-fixa/
       . https://investidor10.com.br/conteudo/tipos-de-investimento-como-funcionam-e-qual-escolher-114020/

   Além disso, o próprio Deep Research criou um relatório geral das informações das fontes, possuindo até bibliografia no final. Ele pode ser encontrado entre as últimas fontes.

   <img width="449" height="869" alt="2026-10-12" src="https://github.com/user-attachments/assets/8348eaf1-2182-4a6f-ba20-009257aabed0" />

   A IA encontrou outras, mas as selecionadas foram apenas as citadas anteriormente, sendo priorizado as de sites que se repetiam, bancos, informações do próprio GOV e PDFs.
   O objetivo central das escolhas era fazer o NotebookLM filtrar as informações que apareciam mais de uma vez e adicionar elementos que poderiam preencher as bordas, como o IPCA Educa+, IPCA Renda+ e FGC, e funcionou bem no decorrer dos testes. Sendo assim, elas se mostraram ter bons dados sobre o assunto.

---

3. 🧪​ **TESTE**

    Neste projeto, foi realizado 4 testes: Perguntas no Chat, vídeo curto, apresentação de slides e áudio, sendo um debate e uma conversa. Abaixo, estarão imagens/áudios/vídeo e comentários sobre cada um.

   -> **_PERGUNTAS COM CHAT_**

   <img width="1920" height="1015" alt="Print 01" src="https://github.com/user-attachments/assets/717dc5b5-0f50-4293-a233-10bca1c91621" />
   <img width="1920" height="1022" alt="Print 02" src="https://github.com/user-attachments/assets/5331fefd-d8ae-4396-9b66-913e01885157" />
   <img width="1920" height="1014" alt="Print 03" src="https://github.com/user-attachments/assets/d7c141ff-d130-4f7c-88de-239170901f1a" />
   <img width="1920" height="1022" alt="Print 04" src="https://github.com/user-attachments/assets/a7477fd9-584c-4739-b4b4-9df525d46b9c" />
   <img width="1920" height="1019" alt="Print 05" src="https://github.com/user-attachments/assets/5baa37bf-ed7f-4fdb-bb3c-eadf2f2a3d15" />
   <img width="1920" height="1017" alt="Print 06" src="https://github.com/user-attachments/assets/41b52ca0-2e84-4659-a10a-07d80659efba" />
   <img width="1920" height="1024" alt="Print 07" src="https://github.com/user-attachments/assets/b87281f8-01cf-49c6-b937-db2d43c86601" />
   <img width="1920" height="1024" alt="Print 08" src="https://github.com/user-attachments/assets/9d9241f5-47b0-4439-bf95-11e0e0055fc7" />
   <img width="1920" height="1019" alt="Print 09" src="https://github.com/user-attachments/assets/313f1eed-cf99-4ae4-8840-143ff6df936e" />

    É possível notar algumas coisas interessantes. Nas primeiras perguntas, o chat utiliza muito as fontes do canal "Primo Pobre" e da "Apostila Investimentos - Harion Camargo", inclusive ambas são citadas no áudio "Renda fixa não é tão fixa assim", que será comentado em seguida. Nas conversas seguintes, o Notebook começou a usar com mais frequência as demais. Tanto em português quanto em inglês o chat funcionou bem, apesar de que quando mudado para o inglês o mesmo continuou a utilizar siglas em português e traduzindo-as. Isso não é exatamente um lado negativo, pensando nas pessoas que querem aprender o idioma americano.

   -> **_ÁUDIO - CONVERSA_**

   . Prompt = Crie uma conversa explicando sobre renda fixa e como usar os investimentos para construir uma vida estável
   
       https://notebooklm.link.google/ur6OJUqYWH0d
   _OBS.: O arquivo de áudio era muito grande para colocar no repositório, então estará acima o link de direcionamento para o NotebookLM!_

   -> **_ÁUDIO - DEBATE_**

   . Prompt = Crie um debate sobre investimentos em renda fixa e quais os cuidados que um investidor iniciante deve ter ao começar

        https://notebooklm.link.google/rrtOquJ0mwfN

   Analisando ambos, é possível notar diversos traços semelhantes e diferentes. Por exemplo, nos dois estilos as vozes criam uma certa interatividade com o ouvinte, fazendo-o pensar e estimulando a prática. Quanto as divergências, o que mais pode-se perceber é a mudança de tonalidade em cada cenário. A conversa é mais fluida, reflexiva e com um ar didático, já o debate carrega um tom mais sério e técnico, com dois lados tentando defender suas visões. Não há brigas, são apenas dois personagens concordando e discordando, encontrando o melhor ponto de equilíbrio entre eles.

   -> **_VÍDEO CURTO_**

   . Prompt = Como calcular rentabilidade líquida real (Sugestão da IA)

     https://github.com/user-attachments/assets/7062d953-3755-4fbe-b65c-cf6eabaec769

   A ideia do teste foi pensada no que domina o mundo hoje, conteúdo curto, mas com informações úteis. A simplicidade das ilustrações e a escolha de palavras da IA formaram uma ótima sinergia, fornecendo tudo que o espectador precisa sobre o assunto.

   -> **_APRESENTAÇÃO DE SLIDES_**

   . Prompt = Crie uma apresentação de slides simples, porem elaborada com todas as principais informações sobre renda fixa e guias para iniciantes

       [Renda_Fixa_Descomplicada.pdf](https://github.com/user-attachments/files/33340541/Renda_Fixa_Descomplicada.pdf)

   Assim como no teste em vídeo, o traço dos slides ficou simples, no entanto didático e seguindo uma linha fluida de conteúdo. Tudo que um investidor iniciante precisa saber sobre a base de investimentos está compilado nesse slide. A única observação é de um erro de escrita na página 07, onde a IA escreveu "naior" ao invés de "maior".

---

4. 💰​ **CONSIDERAÇÕES FINAIS**

    O projeto com NotebookLM foi uma forma de aprender mais sobre Inteligência Artificial e como é possível treina-la para estudar um assunto específico. Só com esta ferramenta, foi possível experimentar muitos conceitos aprendidos até então, desde o que é IA até Engenharia de Prompts, e de bônus um estudo detalhado sobre renda fixa.
    Abaixo, estará o link do Miniguia para fins de curiosidade e pesquisa.
    Vale ressaltar que não foi utilizado uma matriz de comportamento específica aqui, ou seja, uma postura/comportamento adotada para a IA (se comportar como um profissional específico, por exemplo), porem será usado em testes futuros e com outros temas.
    Para quem acompanhou este repositório até o fim, é uma honra ter você aqui!

       LINK DO MINIGUIA = https://notebook.google.com/notebook/8318b5cd-b6e7-4b82-bf45-95157878d725
   














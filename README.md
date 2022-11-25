# Bertoti

<p> "We see three critical differences between programming and software engineering: time, scale, and the trade-offs at play. On a software engineering project, engineers need to be more concerned with the passage of time and the eventual need for change. In a software engineering organization, we need to be more concerned about scale and efficiency, both for the software we produce as well as for the organization that is producing it. Finally, as software engineers, we are asked to make more complex decisions with higher-stakes outcomes, often based on imprecise estimates of time and growth. Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming is certainly a significant part of software engineering: after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming." 


Titus Winters, Software Engineering at Google </p>

<h2> Comentário </h2>

<p> Eu entendi que a engenharia de Software você sempre está preocupado com o desenvolvimento do programa e também a eficiência, se não o programa irá ficar para trás, por conta que a programação sempre cria primeiro e a engenharia está lá para desenvolver na minha concepção.</p>

<br>

<h2> Atividade de Requisitos: Plataforma de ensino </h2>

<h3> Requisitos funcionais: </h3>

<p> • O projeto da Plataforma de Ensino possui como Requisitos Funcionais:<br/> </p>
<p> Ingressar/Criar Reuniões;<br/> </p>
<p> Enviar/Receber Mensagens;<br/> </p>
<p> Criar/Entregar Atividades.;<br/> </p>
    
<h3> 1 - Casos de Uso </h3>

![image](https://user-images.githubusercontent.com/102488914/203879148-48bfc6fd-95af-44d1-b7cf-fa1f4e441b8e.png)
    
<h3> O Diagrama de Casos de Uso é composto por dois atores, Aluno e Professor, e suas possíveis ações na Plataforma de Ensino </h3>

<h3> No primeiro caso com o Aluno, o ator pode fazer 3 ações principais, sendo elas: </h3>

<p> Ingressar em uma Reunião; <br/> </p>
<p> Postar Solução de Atividades/Tarefas; <br/> </p>
<p> Enviar mensagem no Chat Correspondência entre o sistema e o mundo real; <br/> </p>
<p> Já no segundo caso com o Professor, o ator pode fazer 3 ações principais, como; <br/> </p>
<p> Criar uma Atividade/Tarefa; <br/> </p>
<p> Enviar mensagem no Chat; <br/> </p>
<p> Criar uma Reunião; <br/> </p>
    
<h3> Já no segundo caso com o Professor, o ator pode fazer 3 ações principais, como: </h3>

<p> Criar uma Atividade/Tarefa <br/> </p>
<p> Enviar mensagem no Chat <br/> </p>
<p> Criar uma Reunião <br/> </p>

<h3> 2 - User Stories (Cards) </h3>

![image](https://user-images.githubusercontent.com/102488914/203879825-6e565c36-b6a3-46a1-b9f5-3c8639220bc3.png)

<h3> Não-Funcionais </h3>

<br>

<p> O projeto da Plataforma de Ensino possui como Requisitos Não-Funcionais: <br/> </p>
<p> Anexar e deletar arquivo; <br/> </p>
<p> Comunicar com áudio, mensagem e vídeo; <br/> </p>
<p> Compartilhar a tela e seu áudio; <br/> </p>
<p> Ter informações sobre as atividades. <br/> </p>

<h3> TELA 1 - TAREFAS </h3>

<h3> Na tela de Tarefas, é possível identificar as seguintes heurísticas: </h3>

<p> Heurística 2: Correspondência entre o sistema e o mundo real; <br/> </p>
<p> Heurística 3: Controle e liberdade do usuário; <br/> </p>
<p> Heurística 4: Consistência e padrões; <br/> </p>
<p> Heurística 6: Reconhecimento em vez de lembrança; <br/> </p>
<p> Heurística 8: Design estético e minimalista; <br/> </p>
<p> Heurística 10: Ajuda e documentação; <br/> </p>

<h3> TELA 2 - DISCIPLINAS </h3>

<h3> Na tela de Disciplinas, é possível identificar as seguintes heurísticas: </h3>

<p> Heurística 2: Correspondência entre o sistema e o mundo real <br/> </p>
<p> Heurística 3: Controle e liberdade do usuário <br/> </p>
<p> Heurística 4: Consistência e padrões <br/> </p>
<p> Heurística 6: Reconhecimento em vez de lembrança <br/> </p>
<p> Heurística 8: Design estético e minimalista <br/> </p>
<p> Heurística 10: Ajuda e documentação <br/> </p>

<h3> TELA 3 - MENU </h3>

<h3> Na tela de Menu, é possível identificar as seguintes heurísticas: </h3>

<p> Heurística 2: Correspondência entre o sistema e o mundo real <br/> </p>
<p> Heurística 3: Controle e liberdade do usuário <br/> </p>
<p> Heurística 4: Consistência e padrões <br/> </p>
<p> Heurística 6: Reconhecimento em vez de lembrança <br/> </p>
<p> Heurística 8: Design estético e minimalista <br/> </p>
<p> Heurística 10: Ajuda e documentação <br/> </p>

<h2> Projeto </h2>

<h3> Diagrama de Classes - Exemplo Plataforma de Ensino </h3>

![image](https://user-images.githubusercontent.com/102488914/203880523-ccb0be69-0c96-458d-b925-49910b3cc2c6.png)

<h3> Desenvolvimento </h3>

<h3> Classe PlataformaEnsino </h3>

![image](https://user-images.githubusercontent.com/102488914/203880629-b436e3fb-6959-420b-a602-895fb671e244.png)

<h3> Classe Pessoa </h3>

![image](https://user-images.githubusercontent.com/102488914/203880695-47324912-70d8-4d89-ae8d-15b6506300aa.png)

<h3> Classe Disciplina </h3>

![image](https://user-images.githubusercontent.com/102488914/203880779-65ea35ca-5e14-411f-b84b-66bac0fdddb1.png)

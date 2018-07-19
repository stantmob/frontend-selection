# Calendário do mês atual

Você deve criar um calendário do mês atual, organizados pelo dia da semana e gerenciar eventos dinamicamente.

1. Seguir o mockup a seguir:
    ![Main Calendar](/src/images/calendar_main.png "Logo Title Text 1")
    
2. Dias que não pertencem ao mês atual não devem ser exibidos e devem conter um background cinza por padrão e receber uma tonalidade mais escura no hover.
3. O header deve conter os dias da semana com nome reduzido. Deve-se aplicar uma cor de destaque também.
4. Os dias do mês devem ter backound branco branco e uma cor rosada no hover.
5. O dia atual deve receber uma cor de destaque mais escura.

#### Requisitos para gestão dos eventos:

Mockup:
    ![Add Event](/src/images/add_event.png "Logo Title Text 1")

1. Adicionar evento
    * 1.1 Abrir modal de cadastro de evento ao clicar no botão de criar evento
    * 1.2 Os campos necessários são: Título, data/hora de início, data/hora de término e descrição.
    * 1.3 Todos os campos são obrigatórios.
    * 1.4 Fechar modal ao clicar em salvar.
    * 1.5 Adicionar evento no calendário, no dia marcado, baseado no campo da data/hora inicial.
    * 1.6 O evento adicionado no calendário deve ser um resumo da descrição do evento com a quantidade máxima de caracteres que couber no box do dia.
    * 1.7 Adicionar reticências na descrição do evento quando ultrapassar o limite do box.

2. Editar evento
    * 2.1 Abrir formulário de edição com um double click em um evento previamente adicionado ao calendário.
    * 2.2 O modal para edição deverá abrir o formulário com os campos preenchidos no cadastro.
    * 2.3 Atualizar descrição ao clicar em salvar.

 3. Remover evento
    * 3.1 O usuário deverá primeiramente clicar uma vez para selecionar o evento e marcar com uma cor de destaque.
    * 3.2 Exibir modal de confirmação de remoção ao pressionar a tecla backspace.
    * 3.3 Em caso de confirmação, remover evento do calendário com todas as referências previamente salvas.

## Instruções
Todos os dados trabalhados devem ser trabalhados em memória ou com local storage.

Você tem a liberdade de implementar melhorias visuais e de eventos e adicionais.

**Plus opcional:** Você pode implementar também a edição do dia do evento arrastando o elemento para outro dia do calendário.

Após ter finalizado sua implementação, você deverá enviar seu código para o branch em nosso repositório.
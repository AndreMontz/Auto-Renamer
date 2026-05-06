# Auto-Renamer

O Auto-Renamer é um utilitário de produtividade que organiza imagens e GIFs em tempo real. Operando em segundo plano, ele adiciona uma numeração sequencial aos nomes originais dos arquivos conforme eles entram em uma pasta. 

Ideal para quem baixa muitas imagens e precisa mantê-las organizadas cronologicamente por ordem de chegada, sem perder o nome original do arquivo (por exemplo, `image.png` se torna `1-image.png`).

---

## Funcionalidades

* **Operação Invisível:** Roda silenciosamente na bandeja do sistema do Windows. Nenhuma janela aberta para interromper seu fluxo de trabalho.
* **Auto-Start:** Inicia automaticamente com o Windows para que você não precise se lembrar de abri-lo todos os dias.
* **Múltiplos Contadores:** O programa possui memória independente, lembrando exatamente em qual número parou em cada diretório diferente.
* **History (Recent):** Salva as últimas 10 pastas utilizadas para que você possa alternar rapidamente entre elas.
* **Organizational Groups:** Permite salvar e categorizar suas pastas favoritas em grupos personalizados para fácil acesso futuro.
* **Portátil (Standalone):** Não requer instalação do Python ou de bibliotecas extras. Basta executar o arquivo `.exe`.

---

## Como Usar

1. Coloque o arquivo `auto-renamer.exe` em uma pasta de sua escolha.
2. Dê um duplo clique no arquivo para executá-lo.
3. Observe a bandeja do sistema do Windows (canto inferior direito, perto do relógio) e procure por um ícone verde com a letra "R".
4. Clique com o botão direito no ícone para abrir o menu.
5. Selecione a opção **Select Folder** e escolha a pasta onde você fará os downloads ou salvará suas imagens.
6. Pronto! A partir de agora, qualquer imagem salva nessa pasta será numerada automaticamente na ordem em que chegar.

---

## Entendendo o Menu

Ao clicar com o botão direito no ícone do programa, você terá acesso às seguintes opções:

* **Folder in use / Next number:** Mostra o status atual para que você saiba para qual pasta as imagens estão sendo direcionadas e qual será o próximo número aplicado.
* **Select Folder:** Abre o explorador de arquivos para você alterar a pasta que está sendo monitorada.
* **Reset Counter:** Zera a contagem da pasta atual, fazendo com que a próxima imagem volte a receber o número 1.
* **Recent:** Um atalho para acessar rapidamente o histórico de pastas utilizadas. Inclui a opção de limpar este histórico.
* **Groups:** 
    * Use a opção **Save Folder to a Group** para criar categorias (ex.: "Referências", "Memes") e fixar a pasta atual nelas.
    * Através dos submenus, você pode acessar rapidamente as pastas salvas, além de renomear ou excluir os grupos.
* **Language:** Permite alternar o idioma do programa (Português/English).
* **Exit:** Encerra o programa completamente.

---

## Notas Técnicas

* **Extensões Suportadas:** O programa reconhece e renomeia automaticamente arquivos com as seguintes extensões: `.png`, `.jpg`, `.jpeg`, `.gif`, `.bmp`, `.webp` e `.tiff`.
* **Arquivo de Configuração:** Ao ser executado pela primeira vez, o programa criará automaticamente um arquivo chamado `config_renamer.json` no mesmo diretório em que o `auto-renamer.exe` estiver localizado. Este arquivo armazena os seus contadores, histórico de pastas, grupos e preferência de idioma. **Não exclua este arquivo**, ou o programa perderá todo o progresso de numeração salvo.

> **Dica de Uso:** Caso queira pausar o monitoramento do programa temporariamente sem precisar fechá-lo, basta criar uma pasta vazia em qualquer lugar, selecioná-la através do botão **Select Folder** e deixá-la inativa. Alternativamente, clique em **Exit** e abra o programa novamente apenas quando precisar.

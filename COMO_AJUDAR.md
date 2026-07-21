# Como ajudar a desenvolver

Para aqueles que queiram ajudar no desenvolvimento da tradução, um tutorial simplificado

## Requisitos
- O arquivo do jogo original (Versão base EUA: 0004000000086300)
- Editor de .UMSBT (Recomendo o [MSBT Editor](https://msbt-editor.aeonsake.com/))


## Passo a passo
- Faça o dump os arquivos do jogo original. Isso pode ser feito através do [emulador CITRA](https://www.youtube.com/watch?v=siYozu-ki5c)
- Será gerado uma pasta /romfs/0004000000086300/
- Procure pelos arquivos .umsbt pasta Script/Talk ou Script/Str
- Escolha um e abra com o editor de UMSBT
- Selecione o layer 0.msbt, que são os textos em inglês

![Demonstração1](https://i.imgur.com/IZr6WTg.png)
- Basta começar a traduzir, seguindo as regras abaixo

![Demonstração2](https://i.imgur.com/vsE45n8.png)
Após a tradução
![Demonstração3](https://i.imgur.com/tyZ1zLj.png)

- Após toda a alteração no arquivo, salve-o e coloque na pasta equivalente do repositório (Se estava em /romfs/00...0/Script/Talk, coloque no [repositório]/romfs/Script/Talk) e faça o commit.


## Regras
- Não remova os comandos {{}}, pois são usados pelo jogo para definir a reação do personagem durante sua fala, ou definições de texto como tamanho ou parágrafos.
- Não inclua ou remova linhas. O jogo usa a posição da linha do texto original para definir se será um dialogo ou uma resposta do jogador. Se o bloco original conter 4 linhas, a tradução deve conter também 4 linhas.
- O jogo entende a quebra de linha por duas formas, quando uma linha passa de 35 caracteres de texto (comandos não entram na conta) ou com quebra de linha em sí, quando o texto original já utilizava.
- Caso a tradução feita ultrapasse o numero de linhas cabíveis no dialogo original, o texto poderá ser ignorado pelo.
- Não é necessário ser uma tradução 1:1. Pode usar sinonimos ou encurtar falas para caber no formato original. Só lembre-se de manter o mesmo contexto e compreensão
- Vamos tentar manter o nome dos locais originais (Nook's Home, Abble Sisters...) traduzindo apenas as falas
* Quaisquer dúvidas estarei a disposição para tentar ajudar.

# AV2---DIW

Aluna: Susana Oliveira e Telles

Pergunta 1. a) Linha 2: O window.location.search procura a página com determinado id.O get("id") devolve um valor inteiro. Number() foi usado para chamar o número da página com determinado id.
            b) O find recebe o id de um item, enquanto devolve o item de acordo com o id pedido. Quando não encontra o herói ele emite um alerta e uma mensagem: "Item não encontrado". 
            c)
            d) O return vai devolver o item quando ele for encontrado. Se o return fosse apagado, ao abrir detalhes.html?id=99 o código retornará lixo.
Pergunta 2. a) 
            b)
            c) A linha 15 vai devolver a página do tipo procurado, já a linha 16 vai testar se esse tipo está listado nas categorias. Quando abre apenas o index.html não vai retornar nenhum tipourl.
            d) Ao abrir o index.html, o console iria devolver os detalhes de todas as obras listadas no cátalogo.
Pergunta 3. a) As linhas 7 a 15 tem o objetivo de criar os slides e os cards. O operador % indica que o resto da divisão (f.id -1) e qnt vai ser comparado no if. São criados 12 slides com 12 cards.
            b) 
            c)
            d)
Pergunta 4. a) 
            b) O includes indica que eu posso buscar um título por um termo que o compõe, o && indica que tem que atender duas condições buscar por um termo e eu posso buscar por todos os tipos ou, utiliza o ||, por um tipo específico.
            c) No caso 1: id = 3. No caso 3: id = 1 e 5. No caso 3: id = 4 e 6.
            d)
Pergunta 5. a) O tipo de id(linha 2) é um inteiro, já o tipo de f.id é um inteiro também. A comparação da linha 3 encontra o filme pois ela compara o id dos filmes com o id procurado. 
            b) O erro ocorreria na linha 3, a mensagem do console seria algo parecido com "Filme não encontrado". As linhas seguintes não seriam executadas.
            c) 
Pergunta 6. a) O filter vai verificar o destaque de determinado filme, o operador ternário indica que se o id do item for 0 quer dizer que ele está ativo, ou seja é o slide atual
            b)
            c)
Pergunta 7. a) Em precoDoAdicional(show, "Camarote"), o resultado será R$120,00. Em precoDoAdicional(show, "Pipoca"), o resultado vai ser 0, visto que esse nome de adicional não existe. A linha 7 indica que se a linha 6 for verdadeira, ou seja se o nome do adicional for igual ao adicional prourado, eu vou pegar o preço desse adicional.
            b) O primeiro reduce em "Camarote" o valor total será R$120,00. O segundo reduce em "Camarote" e "Copo Oficial" o valor total será R$135,00. O terceiro reduce  em "Camarote", "Copo Oficial" e "Pipoca" o valor total será R$135,00. O 0 ao final da linha 11 indica que se o show não for encontrado em precoDoAdicional retornará o 0 dessa função para ser usado em precoUnitario.
            c) O resultado de quantidadeDoIngresso será R$50,00. O filter vai retornar a linha do id procurado, ou seja nesse caso retornará: id: 1, adicionais: ["Estacionamento"], quantidade: 2. 
            d) O resultado do formatarPreco(precoUnitario(show, ["Estacionamento"])) é R$50,00. O toFixed(2) devolve o valor com duas casas decimais. O papel de reduce é substituir o "." que o sistema manda quando o número é transformado em decimal, para "," no formato padrão.
            

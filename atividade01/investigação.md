# Investigação do site — IF Goiano Campus Ceres

**Site analisado:** https://www.ifgoiano.edu.br/home/index.php/ceres

## 1. Qual site você escolheu e por quê?

Escolhi o site do IF Goiano — Campus Ceres porque ele apresenta informações sobre a instituição, cursos, notícias e serviços para os estudantes.

## 2. Quantas requisições a página fez ao ser carregada?

**Preencher após conferir no navegador:** abra as Ferramentas do Desenvolvedor (`F12`), entre na aba **Rede/Network**, recarregue a página e anote o número indicado no total de requisições, geralmente na parte inferior da lista.

**Total de requisições:** [anotar o valor exibido no navegador]

## 3. Qual foi o método e o código de status da primeira requisição, a do documento?

Na aba **Rede/Network**, clique na primeira requisição correspondente ao documento principal da página e consulte **Cabeçalhos/Headers**.

- **Método:** [anotar o método exibido, por exemplo, GET]
- **Código de status:** [anotar o status exibido, por exemplo, 200]

Não é possível confirmar esses dois valores apenas pela visualização do conteúdo da página; confira-os no navegador.

## 4. Que tipos de arquivo aparecem na lista, além do documento HTML?

Além do documento HTML, a página pode carregar arquivos como **CSS**, **JavaScript**, **imagens** e **fontes**. A lista exata deve ser conferida na aba **Rede/Network**, pois pode variar conforme o carregamento da página e o cache do navegador.

## 5. Alguma requisição retornou código diferente de 200? Qual e o que ele significa?

Confira a coluna **Status** na aba **Rede/Network** e anote se alguma requisição apresentou um código diferente de 200.

- **Resultado observado:** [anotar o código encontrado ou informar que todas as requisições analisadas retornaram 200]
- **Significado:** códigos **3xx** geralmente indicam redirecionamento; códigos **4xx** indicam algum problema na solicitação, como recurso não encontrado (404). O significado exato depende do código recebido.

## 6. O endereço começa com http:// ou https://? O que isso muda?

O endereço começa com **https://**. Isso indica que a conexão utiliza HTTPS, que protege a comunicação entre o navegador e o site por meio de criptografia e ajuda a evitar que os dados sejam lidos ou alterados durante a transmissão.

## 7. Na aba Elementos, localize o título principal da página. Que elemento foi usado?

O título principal do conteúdo é apresentado como um cabeçalho HTML. Para confirmar a tag exata, clique com o botão direito no título da página, escolha **Inspecionar** e confira o elemento destacado na aba **Elementos**. Se estiver marcado como `<h1>`, esse é o elemento utilizado.

## 8. Ative o modo dispositivo e reduza a largura para cerca de 400 pixels. Descreva em duas frases o que muda no layout.

Em uma tela estreita, o conteúdo tende a se reorganizar para caber na largura disponível, com colunas e áreas de conteúdo adaptadas ao formato de celular. Alguns elementos podem ficar empilhados, e o menu e as imagens podem mudar de tamanho ou disposição.

---

## Observação

As respostas das questões **2, 3 e 5** devem ser completadas com os valores observados nas Ferramentas do Desenvolvedor do navegador. A quantidade de requisições e os códigos de status podem variar conforme o momento do acesso, o cache e os recursos carregados.

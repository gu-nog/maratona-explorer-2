# O projeto
### Como está:
![foto após aula 3](exemplo.png)
### Ideia:
Um site que permitirá você acessar uma série de links, permitindo você enviar para outras pessoas e/ou colocar em descrições de redes sociais... apenas o link para nosso projeto
# Aula 1
## Tags:
- Títulos: ```<hx>Título</hx>```, onde x vai de 1 a 6, sendo 1 o 'mais importante da página'
- Parágrafos: ```<p></p>```
- Geral para conter outras tags: ```<div></div>```
- Informações importantes do seu documento, mas que não são mostradas: ```<head></head>```
- Toda estrutura que fica aparente no seu site: ```<body></body>```
- Imagem: ```<img src="local dela" alt="texto para acessibilidade/para se não conseguir carregá-la">```
- Lista não ordenada: ```<ul><ul/>```
- Item das listas: ```<li><li/>```
- Hiperlink: ```<a target="_blank" href="site.alvo"><a/>```
- Quebrar linha: ```</br>```
- Rodapé: ```<footer><footer/>```
## Dicas
- Comentários: ```<!-- -->```
- Quando coloca-se tags dentro de outras tags: aninhamento de tags
- ! + enter - IDE completa para você estrutura padrão de html
## Padrões
- Tags: ```<tag></tag>```
- Tags sem fechamento, exemplo: ```<img ...> ou <img .../>```
# Aula 2

## Propriedades
- alinhamento dos filhos: ```text-align: center```
- largura: ```width: ypx ou y%``` > relativo ao pai
- border: ```border: ypx color solid``` > color e solid(tipo) opicionais
- margin: ```margin: cima direito baixo esquerda``` > auto ele pega o que acha ideal(respeitando demais estilos)
- padding ```padding: = margin```
- padding/border/margin-lado: ```padding-left: ypx```
- Estilo da lista(ex: com bolinhas de tópicos) ```list-style: none```
- como um elemento se comporta aos irmãos(divide linha(inline) ou usa uma única(block)): ```display: inline/block```
- display flex(permite organizar em linhas e/ou colunas os itens) destrava mais algumas propriedades, como:
    - ```justify-content: center``` > em relação à horizontal
    - ```align-item: center``` > em relação à vertical
- cor: ```background/color: #RRGGBB ou red``` > color geralmente quando é inline
- arredondar bordas: ```border-radius: y% ou ypx```
- família das fontes: ```font-family: 'Roboto', sans-serif``` sans serif tira as serifas/arredondadinhas nas pontas
- grossura das fontes: ```font-weight: xxx```
- tamanho das fontes: ```font-size: ypx```
- estilos do texto(grifados etc): ```text-decoration: none```
- formatar texto: ```text-transform: uppercase``` > tudo maiúsculo
- opacidade: ```opacity: 0 a 1```
- velocidade de transição por pseudoclasse: ```transition: propriedade-alterada tempoms```
## Dicas
- Tudo em html são caixas: content>padding>border>margin
- Comentário: ```/**/```
- Se especificidade igual, último que vale
  - classe: múltiplos elementos (.classe) - 10
  - tipo tag: múltiplos elementos (tag) - 1
- Selecionar tudo: *, então pode, por exemplo zerar margin e padding automáticos
  - ```box-sizing: border-box``` padrão é content-box, então se aumentar o tamanho, ex do padding o tamanho do conteúdo manterá com 100% do width/height, no border-box só a margem é desconsiderada
- Adicionar fontes: no fonts.google.com vc seleciona as que quiser depois copia o código e cola no head
- pseudo-classes (:pseudoclasse) só aplicam estilo quando ocorrre algumas circunstãncias
  - ```:hover```: mouse em cima de um hipertexto
# Aula 3
## Dicas:
 - Como salvar propriedades muito repetidas em variáveis: ```--nome-var: valor;```
   - Pra usar: ```var(--nome-var)```
 - color é uma propriedade que passa de pai para filho(aplicar no body aplica em todos textos)
# 🔨 Tecnologias:
    - HTML - linguagem de estruturação(de marcação, não exatamente de programação) de hipertextos(com links)
    - CSS - estilização
# Feito:
- [x] Aula 1
- [x] Aula 2
- [x] Aula 3
---
standalone: true
title: Mapas Livres
slug: mapa
projeto: Mapas Livres
pageSettings:
  language: pt-BR
  link_pt_br: mapas-livres
  link_en: mapas-livres-en
  link_es: mapas-livres-es
  animations: enable_all
  direction: left
  seoTitle: Mapas Livres — infraestrutura aberta para narrativas geográficas
  seoDescription: Uma proposta de infraestrutura aberta para criar, migrar, publicar e preservar mapas e geo-histórias.
  seoKeywords: []
  seoImage: ''
pageTheme:
  primaryColor: '#18332D'
  secondaryColor: '#C95E43'
  highlightColor: '#F4F1EA'
  auxiliaryColor: '#4E7B8B'
  displayFont: ''
  textFont: ''
  spacingPatterns:
    - name: Padrão
      mobile: 10px
      tablet: 11px
      desktop: 12px
pageInclude: null
modules: []
components:
  - type: Group
    id: Capa
    shortTitle: 1. Capa
    longTitle: Capa
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Primary
    customBgColor: ''
    backgroundMedia:
      - type: backgroundImage
        imgSrc: /uploads/map.png
    overlay: light
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### MAPAS LIVRES

                # Infraestrutura aberta para criar, migrar e publicar mapas

                O software livre para mapas já existe.

                **O que falta é torná-lo simples de usar, integrado e realmente acessível para quem precisa de autonomia.**
        column2:
          components:
            - type: Spacer
              desktop: 180px
              tablet: 120px
              mobile: 60px
            - type: Pullquote
              content: Não reinventar a roda. Conectar as tecnologias existentes e melhor a experiência.
              txtColor: ''
              bgColor: ''
              byline: Mapas Livres
      - type: Spacer
        desktop: 80px
        tablet: 60px
        mobile: 40px
  - type: Group
    id: introducao
    shortTitle: 2. Introdução
    longTitle: Infraestrutura aberta para criar, migrar e publicar narrativas geográficas
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Primary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: ''
            - type: HtmlEmbed
              wideHtml: false
              htmlCode: |-
                <head>
                    <meta charset="UTF-8">
                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                    <title>iFrame Mobile Altura Total</title>
                    <style>
                        .container-celular {
                            width: 100%;
                            max-width: 360px; 
                            aspect-ratio: 9 / 16; 
                            margin: 20px auto; 
                            border: 12px solid #222;
                            border-radius: 24px;
                            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
                            overflow: hidden;
                            background-color: #fff;
                            position: relative; 
                        }

                        .container-celular iframe {
                            position: absolute;
                                top: 0;
                                    left: 0;
                                        border: none;
                                            display: block;
                                                
                                                    /* -------------------------------------------------------------
                                                           CONFIGURAÇÃO DE ZOOM (Exemplo para diminuir o zoom para 75%)
                                                                  ------------------------------------------------------------- */
                                                                      
                                                                          /* 1. Altera a base do zoom para o canto superior esquerdo */
                                                                              transform-origin: top left;
                                                                                  
                                                                                      /* 2. Define o nível do zoom (0.75 = 75% do tamanho original) */
                                                                                          transform: scale(0.75);
                                                                                              
                                                                                                  /* 3. MATEMÁTICA DA LARGURA: Divida 100% pelo valor do seu scale (100 / 0.75 = 133.33%) */
                                                                                                      width: 133.333% !important;
                                                                                                          
                                                                                                              /* 4. MATEMÁTICA DA ALTURA: Divida 100% pelo valor do seu scale (100 / 0.75 = 133.33%) */
                                                                                                                  height: 133.333% !important;
                                                                                                                  }
                                                                                                                  
                    </style>
                </head>
                <body>

                    <div class="container-celular">
                        <iframe src="https://documental.xyz/nhanderekoa" title="Visualização Mobile Altura Total"></iframe>
                    </div>
              htmlCaption: 'Nhandereko: Reistência Guarani no Pico do Jaraguá em São Paulo'
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: '## O que essas histórias tem em comum?'
            - type: InnerColumns
              column1:
                components:
                  - type: HtmlEmbed
                    wideHtml: false
                    htmlCode: |-
                      <head>
                          <meta charset="UTF-8">
                          <meta name="viewport" content="width=device-width, initial-scale=1.0">
                          <title>iFrame Mobile Altura Total</title>
                          <style>
                              .container-celular {
                                  width: 100%;
                                  max-width: 360px; 
                                  aspect-ratio: 9 / 16; 
                                  margin: 20px auto; 
                                  border: 12px solid #222;
                                  border-radius: 24px;
                                  box-shadow: 0 10px 25px rgba(0,0,0,0.2);
                                  overflow: hidden;
                                  background-color: #fff;
                                  position: relative; 
                              }

                              .container-celular iframe {
                                  position: absolute;
                                      top: 0;
                                          left: 0;
                                              border: none;
                                                  display: block;
                                                      
                                                          /* -------------------------------------------------------------
                                                                 CONFIGURAÇÃO DE ZOOM (Exemplo para diminuir o zoom para 75%)
                                                                        ------------------------------------------------------------- */
                                                                            
                                                                                /* 1. Altera a base do zoom para o canto superior esquerdo */
                                                                                    transform-origin: top left;
                                                                                        
                                                                                            /* 2. Define o nível do zoom (0.75 = 75% do tamanho original) */
                                                                                                transform: scale(0.75);
                                                                                                    
                                                                                                        /* 3. MATEMÁTICA DA LARGURA: Divida 100% pelo valor do seu scale (100 / 0.75 = 133.33%) */
                                                                                                            width: 133.333% !important;
                                                                                                                
                                                                                                                    /* 4. MATEMÁTICA DA ALTURA: Divida 100% pelo valor do seu scale (100 / 0.75 = 133.33%) */
                                                                                                                        height: 133.333% !important;
                                                                                                                        }
                                                                                                                        
                          </style>
                      </head>
                      <body>

                          <div class="container-celular">
                              <iframe src="https://documental.xyz/expulsions" title="Visualização Mobile Altura Total"></iframe>
                          </div>
                    htmlCaption: 'Expulsões: promovidas por mineradoras na Amazônia Equatorial.'
              column2:
                components:
                  - type: HtmlEmbed
                    wideHtml: false
                    htmlCode: |-
                      <head>
                          <meta charset="UTF-8">
                          <meta name="viewport" content="width=device-width, initial-scale=1.0">
                          <title>iFrame Mobile Altura Total</title>
                          <style>
                              .container-celular {
                                  width: 100%;
                                  max-width: 360px; 
                                  aspect-ratio: 9 / 16; 
                                  margin: 20px auto; 
                                  border: 12px solid #222;
                                  border-radius: 24px;
                                  box-shadow: 0 10px 25px rgba(0,0,0,0.2);
                                  overflow: hidden;
                                  background-color: #fff;
                                  position: relative; 
                              }

                              .container-celular iframe {
                                  position: absolute;
                                      top: 0;
                                          left: 0;
                                              border: none;
                                                  display: block;
                                                      
                                                          /* -------------------------------------------------------------
                                                                 CONFIGURAÇÃO DE ZOOM (Exemplo para diminuir o zoom para 75%)
                                                                        ------------------------------------------------------------- */
                                                                            
                                                                                /* 1. Altera a base do zoom para o canto superior esquerdo */
                                                                                    transform-origin: top left;
                                                                                        
                                                                                            /* 2. Define o nível do zoom (0.75 = 75% do tamanho original) */
                                                                                                transform: scale(0.75);
                                                                                                    
                                                                                                        /* 3. MATEMÁTICA DA LARGURA: Divida 100% pelo valor do seu scale (100 / 0.75 = 133.33%) */
                                                                                                            width: 133.333% !important;
                                                                                                                
                                                                                                                    /* 4. MATEMÁTICA DA ALTURA: Divida 100% pelo valor do seu scale (100 / 0.75 = 133.33%) */
                                                                                                                        height: 133.333% !important;
                                                                                                                        }
                                                                                                                        
                          </style>
                      </head>
                      <body>

                          <div class="container-celular">
                              <iframe src="https://documental.xyz/territorios-de-excecao" title="Visualização Mobile Altura Total"></iframe>
                          </div>
                    htmlCaption: 'Território de Exceção: análise o uso de helicópteros como plataforma de tiro nas favelas do Rio de Janeiro'
  - type: Group
    id: apresentacao
    shortTitle: Apresentação
    longTitle: ''
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 01

                ## Quem somos?
        column2:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ### **Aline Lima**

                Graduanda em Tecnologia da Informação e relações institucionais do IBEBrasil
            - type: Spacer
              desktop: 50px
              tablet: 10px
              mobile: 10px
            - type: Text
              hasDropCap: false
              content: |-
                ### **Thiago Paixão**

                Desenvolvedor de Software, hacker e ativista. Diretor no IBEBrasil
  - type: Group
    id: documental
    shortTitle: Documental
    longTitle: Onde o mapa encontra a narrativa
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Primary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 01

                # DOCUMENTAL

                Texto. Imagem. Vídeo. Dados. Tempo. Território.

                Uma geo-história não precisa escolher entre narrativa e mapa.
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                O Mapas Livres entra como infraestrutura territorial para uma experiência editorial já existente.

                A integração experimental permite que a narrativa combine conteúdo editorial, dados geográficos e mapas livres em uma mesma publicação, mantendo os mapas sob controle dos autores ou organizações.
            - type: Pullquote
              content: O mapa não é o produto final. É um dos elementos de uma narrativa maior.
              txtColor: ''
              bgColor: ''
              byline: Princípio de design da proposta
      - type: Column
        paddingTop: false
        paddingBottom: false
        components:
          - type: Gallery
            description: ''
            uniqid: documental_galery
            images:
              - image: /uploads/captura-de-tela-2026-09-25-132613.png
                caption: ''
              - image: /uploads/captura-de-tela-2026-09-25-132636.png
                caption: ''
              - image: /uploads/captura-de-tela-2026-09-25-132733.png
                caption: ''
              - image: /uploads/captura-de-tela-2026-09-25-132858.png
                caption: ''
  - type: Group
    id: o-ecossistema-ja-existe
    shortTitle: O ecossistema
    longTitle: As peças já existem
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 02

                ## Não queremos substituir uma caixa-preta por outra.
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                O ecossistema geoespacial livre já reúne tecnologias maduras e complementares.

                O desafio é transformar esse conjunto de peças em uma experiência coerente para quem precisa produzir uma publicação, e não estudar toda a infraestrutura geoespacial antes de começar.
            - type: InnerColumns
              column1:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: _blank
                            text: conhecer
                            url: https://maplibre.org/
                          text: Renderização de mapas no navegador sobre uma base aberta.
                          title: MapLibre
                          type: Card
              column2:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: _blank
                            text: conhecer
                            url: https://pmtiles.org/
                          text: Distribuição eficiente de dados geoespaciais em arquivos portáveis.
                          title: PMTiles
                          type: Card
            - type: InnerColumns
              column1:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: _blank
                            text: conhecer
                            url: https://geojson.org/
                          text: Um formato aberto e amplamente utilizado para dados geográficos.
                          title: GeoJSON
                          type: Card
              column2:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: _blank
                            text: conhecer
                            url: https://qgis.org/
                          text: Ferramenta livre para análise, edição e produção cartográfica.
                          title: QGIS
                          type: Card
  - type: Group
    id: mapas-livres
    shortTitle: Mapas Livres
    longTitle: Uma camada de integração
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Primary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 03

                # MAPAS LIVRES

                Uma camada de integração entre ferramentas, formatos e pessoas.

                Não é um novo GIS que tenta fazer tudo.

                É uma infraestrutura que conecta as capacidades que já existem.
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                A proposta parte de uma arquitetura em que dados possam ser portados, mapas possam ser reproduzidos, software possa ser auditado e infraestrutura possa ser autohospedada.

                A experiência deve esconder a complexidade quando isso ajuda — mas nunca esconder as possibilidades de controle.
            - type: Pullquote
              content: Autonomia não significa fazer tudo sozinho. Significa ter alternativas reais.
              txtColor: ''
              bgColor: ''
              byline: Mapas Livres
  - type: Group
    id: maplab
    shortTitle: MapLab
    longTitle: 'O produto: um estúdio visual para mapas livres'
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 04

                ## MAPLAB

                Um estúdio visual para criar, editar, migrar e publicar mapas sem exigir conhecimento especializado em infraestrutura geoespacial.
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                A experiência é inspirada na facilidade de uso de ferramentas como o Mapbox Studio, mas construída sobre uma stack aberta.

                O MapLab funciona como uma porta de entrada para a autonomia: importar projetos existentes, visualizar o que pode ser preservado, adaptar o que depende de serviços proprietários e publicar em uma infraestrutura sob controle da organização.
            - type: InnerColumns
              column1:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: fluxo
                            url: '#'
                          text: Receber projetos existentes e analisar suas dependências.
                          title: Importar
                          type: Card
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: fluxo
                            url: '#'
                          text: Trabalhar visualmente com camadas, estilos e visualizações.
                          title: Editar
                          type: Card
              column2:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: fluxo
                            url: '#'
                          text: Preparar mapas para infraestrutura própria, compartilhada ou local.
                          title: Publicar
                          type: Card
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: fluxo
                            url: '#'
                          text: Conectar mapas livres a narrativas produzidas na Documental.
                          title: Integrar
                          type: Card
      - type: Column
        paddingTop: false
        paddingBottom: false
        components:
          - type: Gallery
            description: ''
            uniqid: maplab
            images:
              - image: /uploads/image1.jpeg
                caption: ''
              - image: /uploads/image2.jpeg
                caption: ''
              - image: /uploads/image3.jpeg
                caption: ''
              - image: /uploads/image4.jpeg
                caption: ''
  - type: Group
    id: jornada-de-migracao
    shortTitle: Migração
    longTitle: A migração como porta de entrada
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 05

                ## A migração não é o fim.

                É a porta de entrada para a autonomia.
        column2:
          components:
            - type: Timeline
              txtColor: ''
              bgColor: ''
              components:
                - type: TimelineBullet
                  text: 01 — Importar
                  content: Importar o projeto existente e identificar estilos, camadas, fontes de dados e dependências.
                - type: Spacer
                  desktop: 50px
                  tablet: 50px
                  mobile: 30px
                - type: TimelineBullet
                  text: 02 — Analisar
                  content: Separar o que é dado, o que é estilo e o que depende de serviços externos.
                - type: Spacer
                  desktop: 50px
                  tablet: 50px
                  mobile: 30px
                - type: TimelineBullet
                  text: 03 — Adaptar
                  content: Substituir dependências proprietárias por formatos e componentes abertos quando possível.
                - type: Spacer
                  desktop: 50px
                  tablet: 50px
                  mobile: 30px
                - type: TimelineBullet
                  text: 04 — Editar
                  content: Visualizar e editar o resultado em uma interface amigável.
                - type: Spacer
                  desktop: 50px
                  tablet: 50px
                  mobile: 30px
                - type: TimelineBullet
                  text: 05 — Publicar
                  content: Publicar em infraestrutura própria, compartilhada ou distribuída localmente.
                - type: Spacer
                  desktop: 50px
                  tablet: 50px
                  mobile: 30px
                - type: TimelineBullet
                  text: 06 — Narrar
                  content: Integrar o mapa a uma geo-história Documental.
  - type: Group
    id: arquitetura
    shortTitle: Arquitetura
    longTitle: Uma arquitetura que cabe em diferentes territórios
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 06

                ## A mesma publicação pode assumir diferentes formas de infraestrutura.
            - type: Text
              hasDropCap: true
              content: |-
                O projeto nasce pensando em diferentes condições de conectividade e operação.

                A conveniência de um serviço gerenciado não precisa eliminar a autonomia de quem deseja operar a própria infraestrutura.
        column2:
          components:
            - type: InnerColumns
              column1:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: modelo
                            url: '#'
                          text: A organização controla seus próprios dados, mapas e infraestrutura.
                          title: Autohospedada
                          type: Card
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: modelo
                            url: '#'
                          text: Instalação em infraestrutura já existente.
                          title: Servidor próprio
                          type: Card
              column2:
                components:
                  - type: Cards
                    cardsArr:
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: modelo
                            url: '#'
                          text: Distribuição em ambientes com conectividade limitada.
                          title: Rede local
                          type: Card
                      - Card:
                          icon: ''
                          link:
                            customTarget: ''
                            target: ''
                            text: modelo
                            url: '#'
                          text: Uma camada de conveniência sem retirar a possibilidade de saída.
                          title: Serviço gerenciado
                          type: Card
  - type: Group
    id: por-que-importa
    shortTitle: Impacto
    longTitle: Por que infraestrutura também é uma questão de direitos
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 08

                ## Quem controla a infraestrutura também controla parte das possibilidades de publicação.
            - type: Text
              hasDropCap: true
              content: |-
                Para organizações que documentam violações, conflitos, transformações territoriais e processos históricos, dependência tecnológica pode significar dependência sobre onde e como uma narrativa pode continuar disponível.

                Mapas Livres busca ampliar alternativas: portabilidade, auditabilidade, autohospedagem, publicação estática e operação em diferentes condições de conectividade.
        column2:
          components:
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Portabilidade
                    text: Os dados e mapas podem ser preparados para sair de uma infraestrutura específica.
                    link:
                      url: '#'
                      target: ''
                      customTarget: ''
                      text: princípio
                    icon: ''
                - Card:
                    type: Card
                    title: Reprodutibilidade
                    text: A publicação deve poder ser reconstruída a partir de seus componentes.
                    link:
                      url: '#'
                      target: ''
                      customTarget: ''
                      text: princípio
                    icon: ''
                - Card:
                    type: Card
                    title: Auditabilidade
                    text: A arquitetura e o software devem poder ser examinados e adaptados.
                    link:
                      url: '#'
                      target: ''
                      customTarget: ''
                      text: princípio
                    icon: ''
                - Card:
                    type: Card
                    title: Resiliência
                    text: A publicação deve continuar possível em diferentes condições de infraestrutura.
                    link:
                      url: '#'
                      target: ''
                      customTarget: ''
                      text: princípio
                    icon: ''
  - type: Group
    id: mvp
    shortTitle: MVP
    longTitle: O que queremos demonstrar
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 33-66
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 09

                ## Um protótipo pequeno, mas de ponta a ponta.
        column2:
          components:
            - type: Text
              hasDropCap: true
              content: |-
                A primeira entrega não precisa resolver todo o ecossistema.

                Ela precisa provar o caminho: **importar → entender → adaptar → editar → publicar → integrar**.
            - type: Timeline
              txtColor: ''
              bgColor: ''
              components:
                - type: TimelineBullet
                  text: Entrada
                  content: Projeto de mapa existente entra no fluxo.
                - type: Spacer
                  desktop: 40px
                  tablet: 40px
                  mobile: 25px
                - type: TimelineBullet
                  text: Diagnóstico
                  content: Dependências e elementos preserváveis são identificados.
                - type: Spacer
                  desktop: 40px
                  tablet: 40px
                  mobile: 25px
                - type: TimelineBullet
                  text: Edição
                  content: Uma visualização aberta pode ser ajustada visualmente.
                - type: Spacer
                  desktop: 40px
                  tablet: 40px
                  mobile: 25px
                - type: TimelineBullet
                  text: Publicação
                  content: O mapa pode ser preparado para publicação em infraestrutura controlada.
                - type: Spacer
                  desktop: 40px
                  tablet: 40px
                  mobile: 25px
                - type: TimelineBullet
                  text: Geo-história
                  content: A publicação pode alimentar uma narrativa Documental.
  - type: Group
    id: sustentabilidade
    shortTitle: Sustentabilidade
    longTitle: Autonomia não precisa significar isolamento
    description: ''
    showInMenu: true
    animations: true
    txtColor: Primary
    customTxtColor: ''
    bgColor: Highlight
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                ###### 10

                ## Um caminho sustentável pode começar pequeno.
            - type: Text
              hasDropCap: true
              content: |-
                A arquitetura proposta permite diferentes modelos de operação.

                Uma organização pode começar com infraestrutura própria ou compartilhada e, no futuro, optar por uma camada de serviço gerenciado — sem transformar essa conveniência em dependência obrigatória.
        column2:
          components:
            - type: Cards
              cardsArr:
                - Card:
                    type: Card
                    title: Comunidade
                    text: Software, formatos e conhecimento reutilizáveis por diferentes organizações.
                    link:
                      url: '#'
                      target: ''
                      customTarget: ''
                      text: caminho
                    icon: ''
                - Card:
                    type: Card
                    title: Infraestrutura compartilhada
                    text: Custos de operação podem ser distribuídos entre organizações e projetos.
                    link:
                      url: '#'
                      target: ''
                      customTarget: ''
                      text: caminho
                    icon: ''
                - Card:
                    type: Card
                    title: Serviço gerenciado
                    text: Uma possibilidade futura para quem busca conveniência sem abrir mão da portabilidade.
                    link:
                      url: '#'
                      target: ''
                      customTarget: ''
                      text: caminho
                    icon: ''
  - type: Group
    id: fechamento
    shortTitle: Fechamento
    longTitle: Criar. Migrar. Publicar. Preservar.
    description: ''
    showInMenu: true
    animations: true
    txtColor: Highlight
    customTxtColor: ''
    bgColor: Secondary
    customBgColor: ''
    backgroundMedia: []
    overlay: none
    components:
      - type: Columns
        paddingTop: true
        paddingBottom: true
        invertOnMobile: false
        columnsAlign: 66-33
        column1:
          components:
            - type: Text
              hasDropCap: false
              content: |-
                # Criar.
                # Migrar.
                # Publicar.
                # Preservar.
        column2:
          components:
            - type: Pullquote
              content: O território é nosso. Os dados são nossos. A infraestrutura também pode ser.
              txtColor: ''
              bgColor: ''
              byline: Mapas Livres
            - type: Spacer
              desktop: 80px
              tablet: 60px
              mobile: 40px
            - type: Text
              hasDropCap: false
              content: |-
                **MAPAS LIVRES**

                Infraestrutura aberta para criar, migrar e publicar narrativas geográficas


                Hackathona Festival Compartilhe!
      - type: Spacer
        desktop: 120px
        tablet: 100px
        mobile: 60px
---

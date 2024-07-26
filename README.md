# Projeto_de_Estudo_Agrícola_Classificacao_Muiticlasse_Folhas_Cultivo_Milho_Rede_Neural_Artificial_CNN
Este Projeto de Estudo tem por objetivo estudar as Redes Neurais Artificiais Convolucionais CNN, para identificação de pragas em folhas do cultivo de milho, podendo o algorítmo ser uma aplicação para auxiliar a identificação de pragas contribuindo para a tomada de decisão, quanto ao uso correto de agentes químicos no combate destas pragas.


![Capa_Projeto_Estudo_Agrícola_Milho_Redes_Neurais_CNN](https://github.com/user-attachments/assets/6ca2ce1f-7733-4252-a8fe-ff86f9c8d096)

# Introdução:

O milho é uma das culturas alimentares mais importantes, posicionando-se logo após o arroz em termos de relevância global. Esta planta destaca-se pela sua alta produtividade e ampla versatilidade de uso, o que a torna essencial na alimentação e em diversas indústrias. O cultivo do milho é viável em uma variedade de climas, tanto quentes quanto frios, desde que haja um bom sistema de irrigação para suportar o desenvolvimento das plantas.

Durante o ciclo de vida do milho, que vai desde a germinação da semente até a produção de novas sementes, cada parte da planta é suscetível a uma série de doenças. As folhas, em particular, são altamente vulneráveis a patógenos que podem afetar severamente a saúde da planta. Essas doenças foliares resultam em uma diminuição significativa na quantidade e na qualidade da colheita, comprometendo o rendimento final e a produtividade da cultura de milho. Portanto, o manejo eficaz dessas doenças é crucial para garantir uma produção sustentável e de alta qualidade.

# Pragas e Condições das Folhas de Uma Plantação de Milho:

As folhas de uma plantação de milho desempenham um papel crucial na fotossíntese, o processo pelo qual a planta converte luz solar em energia química. Folhas saudáveis são essenciais para a produção máxima de grãos, pois permitem a captura eficiente da luz solar e a troca de gases necessários para o crescimento da planta. Folhas saudáveis são caracterizadas por uma cor verde vibrante, ausência de manchas ou lesões, e uma superfície lisa. Essas condições indicam uma planta bem nutrida e livre de estresses patogênicos.

A queimadura foliar é uma condição frequentemente causada por estresse hídrico ou térmico, onde as folhas apresentam áreas necrosadas e secas, geralmente nas margens e pontas. Esse fenômeno pode ocorrer devido à exposição prolongada a temperaturas elevadas, baixa umidade ou irrigação inadequada. A queimadura foliar reduz a área fotossintética ativa da planta, resultando em menor produção de energia e, consequentemente, em uma diminuição no rendimento de grãos.

A mancha foliar do milho, por sua vez, é causada por diversos patógenos fúngicos, como Bipolaris maydis e Exserohilum turcicum. Essas doenças se manifestam como manchas pequenas, irregulares e de cor marrom ou preta nas folhas, que podem coalescer em lesões maiores. A infecção severa pode levar à morte precoce das folhas, diminuindo a capacidade fotossintética da planta e afetando negativamente o desenvolvimento e o rendimento dos grãos. O controle da mancha foliar geralmente envolve práticas de manejo integrado, como a rotação de culturas, uso de cultivares resistentes e aplicação de fungicidas.

A ferrugem foliar do milho é outra doença fúngica significativa, causada principalmente pelos patógenos Puccinia sorghi e Puccinia polysora. Essa doença é identificada pela presença de pústulas pequenas, circulares e de cor marrom-avermelhada na superfície das folhas. As pústulas liberam esporos que podem se espalhar rapidamente, especialmente em condições de alta umidade e temperaturas moderadas. A ferrugem foliar pode causar desfolhamento prematuro, resultando em uma redução drástica na eficiência fotossintética e no rendimento da cultura. Medidas de controle incluem o uso de fungicidas específicos e o plantio de variedades de milho com resistência genética à ferrugem.

Podemos entender que, a saúde das folhas de milho é fundamental para a produtividade da cultura. Condições adversas e doenças foliares, como queimadura foliar, mancha foliar e ferrugem foliar, podem comprometer seriamente a produção de grãos. A implementação de estratégias de manejo integrado é essencial para manter a saúde das folhas e garantir colheitas abundantes e de alta qualidade.

# Sobre o Data Set ou Data Frame:

Os dados foram coletados diretamente de um campo de milho com uma área de aproximadamente 10 hectares, localizado na Vila Polagan, Distrito de Sampang, e pertencente ao Departamento de Agricultura. Esses dados foram combinados com informações sobre doenças foliares do milho. As imagens das folhas de milho foram capturadas usando uma câmera de celular com resolução de 16 megapixels. Para facilitar a classificação e evitar interferências de outros objetos, um papel branco foi colocado atrás das folhas durante a sessão de fotos. Cada folha foi fotografada cinco vezes. As sessões de fotos ocorreram durante o dia, entre 12h e 14h WIB, para garantir boas condições de iluminação.

Os dados utilizados consistem em imagens RGB, totalizando 4000 imagens, com cada classe contendo 1000 pontos de dados. As quatro classes nos dados são: folhas saudáveis, queimadura foliar, mancha foliar e ferrugem foliar. A rotulagem dos dados foi realizada por representantes do Departamento de Horticultura e Agricultura de Plantação do Distrito de Sampang. Esses dados foram validados com uma declaração assinada pelo coordenador do POPT (Observação de Pragas e Doenças de Plantas) do Distrito de Sampang.

# Sobre a Região Geográfica do Plantio da Cultura do Milho que Gerou Este Conjunto de Dados Por Imagem:

A Vila Polagan está situada no Distrito de Sampang, que faz parte da Província de Java Oriental, na Indonésia. Este país, localizado no sudeste da Ásia, é o maior arquipélago do mundo, composto por mais de 17.000 ilhas. Java Oriental é uma das regiões mais densamente povoadas e economicamente significativas da Indonésia, conhecida por sua agricultura diversificada e indústrias em crescimento.

O Distrito de Sampang é uma das várias regiões administrativas dentro da Província de Java Oriental. A economia local é amplamente baseada na agricultura, com cultivos como arroz, milho e tabaco sendo predominantes. Além disso, a região é conhecida pela criação de gado e pela pesca, atividades que sustentam a economia local e garantem a subsistência de muitos de seus habitantes. O distrito possui uma infraestrutura agrícola bem desenvolvida, com vários programas governamentais destinados a melhorar a produtividade e a sustentabilidade das práticas agrícolas.

O Departamento de Agricultura do Distrito de Sampang desempenha um papel vital no apoio aos agricultores locais. Este departamento é responsável por implementar políticas agrícolas, fornecer assistência técnica e promover inovações no setor agrícola. Através de diversos programas, o departamento trabalha para aumentar a produtividade, melhorar a qualidade dos produtos agrícolas e garantir a segurança alimentar na região. Além disso, o Departamento de Agricultura colabora com instituições de pesquisa e organizações não-governamentais para desenvolver e disseminar práticas agrícolas sustentáveis e inovadoras.

A Vila Polagan, sendo uma comunidade agrícola dentro deste distrito, beneficia-se das iniciativas e do suporte fornecido pelo Departamento de Agricultura. Os agricultores locais têm acesso a treinamentos, recursos e tecnologias que ajudam a melhorar a eficiência e a qualidade de suas produções. A colaboração estreita entre a comunidade agrícola de Polagan e o Departamento de Agricultura é fundamental para o desenvolvimento econômico e a sustentabilidade da região, assegurando que a agricultura continue a ser uma base sólida para a economia local.

# Créditos do Autor do Data Set:

* Sandi Indika Saputra. (2023). Corn Leaf Disease [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/6341289


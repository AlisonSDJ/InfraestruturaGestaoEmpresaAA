Em construção...falta colocar imagens das retaguardas, do rack(principal) e do rack do dvr1.

**1. Visão Geral**

- Objetivo do Projeto

O objetivo deste projeto foi reestruturar e implantar toda a infraestrutura de TI de um supermercado, planejando soluções aderentes às demandas técnicas e operacionais, com foco em estabilidade, organização e continuidade das operações. Paralelamente, conduzi a implantação do sistema ERP e realizei o treinamento dos colaboradores, visando padronizar rotinas e processos nos setores Comercial, Financeiro, Entrada e Saída de Notas, Vendas e Administrativo.

- Cenário encontrado

Ambiente com necessidade urgente de intervenções técnicas, operando com 4 PDVs, 4 retaguardas e 1 servidor, além de uma infraestrutura de rede cabeada e wireless mal dimensionada, mal projetada e executada, comprometendo a estabilidade e o desempenho das operações.

- Desafios

Toda a reforma da loja foi realizada com a unidade em pleno funcionamento. Por esse motivo, diversas etapas da infraestrutura de TI precisaram ser executadas com planejamento prévio e janelas controladas, garantindo que os serviços essenciais não fossem interrompidos. Em muitos momentos, atividades como cabeamento estruturado, instalação de câmeras, implantação de PDVs e configuração de equipamentos tiveram que ser realizadas no período noturno, minimizando impactos na operação. Além disso, foi identificado que a empresa não utilizava adequadamente o ERP vigente, principalmente devido à ausência de treinamento e padronização de rotinas, o que exigiu um trabalho adicional de capacitação e organização dos processos internos.

**2. Escopo entregue**

- Rede

A infraestrutura de rede foi planejada com dois racks dedicados a dados, visando maior organização, segmentação e facilidade de manutenção. No Rack A (principal), foi instalada uma MikroTik RB951G-2HnD, responsável pelo gerenciamento completo do ambiente, incluindo firewall, controle da LAN, segmentação por VLANs, failover e administração dos links de internet fornecidos pelos ISPs. A partir desse rack, a conectividade é distribuída para as 9 retaguardas, 2 access points, telefonia VoIP, servidor e um dos DVRs, além de realizar o cascateamento (uplink) para o switch localizado no rack de acesso.

No Rack B (acesso), foi instalado um switch de distribuição, responsável por atender os 8 PDVs e também um dos DVRs, garantindo conectividade estruturada, padronizada e adequada aos pontos críticos da operação.

Para o ambiente de CFTV, os dois DVRs foram organizados em dois racks exclusivos, assegurando melhor organização física, separação dos equipamentos de segurança eletrônica e maior facilidade de manutenção.

- PDVs e Retaguardas

A estrutura foi dimensionada e implantada com 9 retaguardas em Windows e 8 PDVs em Linux, assegurando padronização do parque, compatibilidade com o ERP e estabilidade para as operações de venda e retaguarda.

- CFTV

O sistema de CFTV foi estruturado em dois blocos, distribuídos entre dois DVRs. O DVR 1 (Intelbras iMHDX 3116) ficou responsável pelo monitoramento das seções da loja e área de PDVs, enquanto o DVR 2 foi destinado ao monitoramento dos ambientes administrativos, áreas de acesso restrito e pontos específicos da loja. O DVR 2 foi reaproveitado, pois já fazia parte da infraestrutura existente. Ao todo, foram instaladas 42 câmeras, sendo 32 analógicas e 10 IP.

- Videowall

Foi implantado um sistema de videowall com o objetivo de divulgar preços e ofertas dos produtos do açougue. Para isso, utilizei o MIT 7 da Toledo, equipamento responsável pela gestão e distribuição de mídia interna. A partir do MIT, o conteúdo passou a ser exibido em 3 TVs instaladas no setor de açougue, garantindo comunicação visual padronizada e atualização prática das campanhas promocionais.

- ERP

A loja utilizava o ERP da G10 Sistemas, porém, devido a necessidades relacionadas às rotinas e aos processos operacionais, foi necessária a migração para uma nova solução. Após avaliação e reuniões com fornecedores, o ERP da VR Software foi escolhido para apoiar e dar suporte aos processos de gestão da loja. 

Participei de todo o processo de implantação, desde a liberação de acessos para que a equipe da VR Software realizasse a extração e importação de dados do sistema anterior, até o acompanhamento e orientação sobre quais informações deveriam ser migradas. Também atuei na instalação e configuração das aplicações nas retaguardas e PDV's, além de conduzir o treinamento dos colaboradores, garantindo a padronização do uso do sistema e das rotinas operacionais.

- Cartão marca própria

Com foco em competitividade de mercado, fortalecimento da identidade da marca e melhor controle da inadimplência, a empresa decidiu implantar um cartão de crédito de marca própria. Fiquei responsável pela prospecção e avaliação de empresas parceiras e, entre as opções analisadas, a UZE foi a escolhida.

Conduzi, com apoio da equipe de implantação da UZE, todo o processo de criação do cartão, incluindo a preparação dos PDVs para aceitação da nova modalidade de pagamento e o treinamento da equipe financeira, responsável pela gestão de pagamentos, recebimentos e rotinas administrativas relacionadas ao cartão.

Além disso, também participei das ações de divulgação interna e externa, com iniciativas como carro de som, panfletagem e outdoor, visando a captação de novos clientes e a adesão ao cartão.

**3. Fotos**

Balança destinada a sessão de produtos naturais e temperos.
<img src="assets/img/Balança destinada a sessão de produtos naturais e temperos..jpg" width="900">

Balanças do açougue.
<img src="assets/img/Balanças do açougue..jpg" width="900">

Câmeras monitorando algumas sessões da loja.
<img src="assets/img/Câmeras monitorando algumas sessões da loja..jpg" width="900">

Cãmeras monitorando algumas sessões 2.
<img src="assets/img/Cãmeras monitorando algumas sessões 2.jpg" width="900">

Rack CFTV2.
<img src="assets/img/Rack CFTV2.jpg" width="900">

Rack(Acesso) e Rack(CFTV2).
<img src="assets/img/Rack(Acesso) e Rack(CFTV2)..jpg" width="900">

Rack(Acesso) visão interna do cabeamento.
<img src="assets/img/Rack(Acesso) visão interna do cabeamento..jpg" width="900">

Rack(Acesso)
<img src="assets/img/Rack(Acesso).jpg" width="900">

Relógio de Ponto.
<img src="assets/img/Relógio de Ponto.jpg" width="900">

Retaguarda com 2 impressoras de etiqueta.
<img src="assets/img/Retaguarda com 2 impressoras de etiqueta..jpg" width="900">

TV para monitoramento das câmeras da loja.
<img src="assets/img/TV para monitoramento das câmeras da loja..jpg" width="900">

Videowall com 3 TVS mostrando os valores dos produtos.
<img src="assets/img/Videowall com 3 TVS mostrando os valores dos produtos..jpg" width="900">

Visando de um consulta preço.
<img src="assets/img/Visando de um consulta preço..jpg" width="900">

Visão de 1 dos 4 consulta preços instalados.
<img src="assets/img/Visão de 1 dos 4 consulta preços instalados..jpg" width="900" height="600">

Visão de 7 dos 8 PDV's.
<img src="assets/img/Visão de 7 dos 8 PDV's..jpg" width="900">

Vídeowall com 3 TV's mostrando preços dos produtos e ofertas.
<img src="assets/img/Vídeowall com 3 TV's mostrando preços dos produtos e ofertas..jpg" width="900">

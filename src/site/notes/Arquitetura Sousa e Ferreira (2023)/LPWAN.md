---
{"dg-publish":true,"permalink":"/arquitetura-sousa-e-ferreira-2023/lpwan/"}
---

LoRaWAN:

1. Camada dos equipamentos emissores: onde se inserem todos os equipamentos emissores de dados via LoRaWAN; 

2. Gateway: para a criação da rede LoRaWAN é necessário serem instaladas uma ou várias gateways. Estes equipamentos são responsáveis por recolher os sinais rádio provenientes dos sensores e enviar os dados para a camada seguinte; 
3. Servidor de rede: esta camada é responsável por desencriptar os pacotes recebidos pelas gateways da camada anterior, uma vez que todos os dados até aqui se encon tram devidamente protegidos. Apenas o servidor de rede que possua as chaves de acessos a estes dados é que conseguirá interpretá-los e, posteriormente, integrá-los noutro sistema; 
4. Servidor aplicacional: nesta camada estão presentes os diferentes serviços que recebem os dados desencriptados e os tratam de formas diversas
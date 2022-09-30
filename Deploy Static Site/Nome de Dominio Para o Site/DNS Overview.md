# DNS Overviews
Vamos revisar sua configuração de DNS até agora.

No Route 53, a Zona hospedada do seu nome de domínio contém o seguinte:

O registro NS (Name Server) para seu nome de domínio. Quando um nome de domínio é digitado em um navegador, o DNS procura esses servidores de nome para ajudar a direcionar a solicitação.

O registro A (ou Alias). Esse registro é usado para direcionar solicitações do seu nome de domínio para os servidores do GitHub usando seus endereços IP.

O registro CNAME (ou nome canônico). Esse registro especifica qual domínio personalizado apontará para seu domínio verdadeiro (canônico).

![image](/Images/DNS.png)
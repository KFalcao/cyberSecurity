Habilidades medidas pelo Exame e percentual de quanto cai na prova.

Descrever os conceitos de segurança, conformidade e identidade = 10 a 15%.
Descrever as capacidades do Microsoft Entra = 25 a 30%.
Descrever as funcionalidades das soluções de segurança da Microsoft =  25 a 30%.
Descrever as funcionalidades do Microsoft Priva e do Microsoft Purview = 25 a 30%.

Aula 01:
Conceitos de Segurança e conformidade
Conceitos de identidade

----------------------------------------------------------------------------------------

Módulo 01

- Modelo de responsabilidade compartilhada

As reponsabilidades variam dependendo de onde está a Workload:

    - SaaS (Software as a Service - Software como serviço)
    - PaaS (Platform as a Service - Plataforma como serviço)
    - IaaS (Infrastructure as a Service - Infraestrutura como serviço)
    - Datacenter local

![alt text](image.png)

# Defense-in-depth (DiD) - Defesa em Profundidade

![alt text](image-2.png)

A defense-in-depth usa uma abordagem em camadas para a segurança, os exemplos incluem:

 - Segurança física (Physical): Locks, fences and security guards | limitar o acesso a um datacenter somente ao pessoal autorizado.

 - Segurança de identidade e acesso(Policies, procedures and awareness): Passwords, policies and data classification | Controla o acesso à infraestrutura e o controle de alterações.

 - Segurança de perímetro (perimeter): Firewall, VPN and Packet filters | proteção contra DDoS(negação de serviõ distribuída) para filtrar ataques em grande escala antes que eles possam causar uma interrupção para os usuários.

 - Segurança de rede(internal network): Firewall intrucion detection and encryption | limita a comunicação entre recursos por meio da segmentação e dos controles de acesso.

 - Segurança da camada de computação(Host): Platform OS, patches and malware protection | protege o acesso a máruinas virtuais fechando determinadas portas.

 - Segurança da camada de aplicativo(App): SSO, authentication and authorization | verifica se os aplicativos estão seguros e livres de vulnerabilidades.

 - Segurança da camada de dados(Data): Database, content and message security | controla o acesso a dados comerciais e de clientes e usa criptografia para proteger dados.


## CIA / CID - Confidentiality, Integrity, and Availability | Confiabilidade, Integridade E Disponibilidade
### A Triade da Segurança Cibernética!

![alt text](image-1.png)

CIA - os objetivos de uma estratégia de segurança cibernética. - Base da segurança da informação.

 *Confidentiality | Confidencialidade*: Garantia que dados confidenciais como informações do cliente, permaneçam confidenciais.

 *Integrity | Integridade*: Garantia que dados ou mensagens não tenham sido adulterados.

 *Availability | Disponibilidade*: Significa a disponibilização de dados àqueles que precisam deles.


 ## O Modelo Zero Trust

 #### Princípios de orientação de Zero Trust (Confiança 0)

  - Verificação explícita
  - Acesso com privilégio Mínimo
  - Assumir violação

#### Seis pilares fundamentais
  - As **identidades** (humana e não humana) e podem ser usuários, serviços ou dispositivos.
  - Os **dispositivos** (máquinas - windows, linux, mac | android, Ios)criam uma grande superfície de ataque à medida que os dados fluem, diferentes dispositivos necessitam de diferentes tipos de controle, não conseguimos colocar as mesmas politicas de proteção para todos.
  - Os **aplicativos** (SaaS)são a maneira como os dados são consumidos.
  - Os **dados** devem ser classificados, rotulados e criptografados.
  - A **infraestrutura** se representa um vetor de ameaça.
  - AS **redes** devem ser segmentadas, acesando apenas o que devem acessar.
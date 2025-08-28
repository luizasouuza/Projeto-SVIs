🧠 Descrição do Projeto

Este é um dos projetos desenvolvidos utilizando topologia de VLANs para implementar o conceito de SVI (Switched Virtual Interface). O principal objetivo foi segmentar a rede em diferentes domínios de broadcast, utilizando roteamento inter-VLAN por meio de um switch Layer 3 (Multilayer Switch).

🛠️ Componentes Utilizados

Switch Layer 3 (Multilayer Switch) para roteamento entre VLANs

Switches Layer 2 (2960) para interligação dos dispositivos finais

Computadores e Servidor com endereços IP configurados estaticamente

Cisco Packet Tracer como ambiente de simulação

🌐 VLANs Configuradas

VLAN	Nome (cor do grupo)	Sub-rede

10	Verde	192.168.10.0/24

20	Azul	192.168.20.0/24

30	Roxo	192.168.30.0/24

40	Amarelo	192.168.40.0/24

Cada PC foi alocado em uma VLAN específica e configurado com IP compatível com a sua sub-rede. O roteamento inter-VLAN foi habilitado no Switch Layer 3 por meio da criação de interfaces virtuais (SVIs), uma para cada VLAN.

⚙️ Funcionalidades Implementadas

- Segmentação de rede por VLANs

- Comunicação entre dispositivos da mesma VLAN

- Roteamento entre VLANs via SVI

- Gerenciamento de tráfego com switches L2 e L3

📸 Imagem da Topologia

🖥️ Topologia Geral da Rede com SVIs

<img width="1655" height="737" alt="Image" src="https://github.com/user-attachments/assets/a2039455-df41-4f20-af78-9e6ad1c0d45f" />

📶 Teste de Conectividade (Ping entre Computadores)

Ping executado entre máquinas de diferentes VLANs, comprovando que o roteamento inter-VLAN via SVI está funcionando corretamente:

<img width="650" height="297" alt="Image" src="https://github.com/user-attachments/assets/c70dd455-1a9b-44cb-b982-4925b02aa32e" />

🌐 Acesso Web ao Servidor

Os computadores também conseguiram acessar o servidor web interno, confirmando a comunicação entre VLANs:

<img width="695" height="381" alt="Image" src="https://github.com/user-attachments/assets/9169e803-0d78-44cc-871b-db0af4f36957" />

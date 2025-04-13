# Veja alguma vantagens de criar uma máquina virtual (VM) no Azure que  oferece uma série de vantagens para indivíduos e empresas, proporcionando flexibilidade, escalabilidade e eficiência na gestão de recursos de computação. Aqui estão alguns dos principais benefícios:

1. Escalabilidade e Flexibilidade:

Dimensionamento sob demanda: O Azure permite aumentar ou diminuir os recursos da VM de acordo com as necessidades, evitando o investimento em hardware subutilizado.
Variedade de configurações: É possível escolher entre uma ampla gama de configurações de hardware e sistemas operacionais, adaptando a VM a diferentes cargas de trabalho.

2. Redução de Custos:
Modelo de pagamento por uso: Pague apenas pelos recursos que você utiliza, eliminando custos com infraestrutura física e manutenção.
Opções de economia: O Azure oferece programas como o Benefício Híbrido do Azure e VMs de Spot, que permitem reduzir os custos.

3. Alta Disponibilidade e Confiabilidade:
Infraestrutura global: A rede global de data centers do Azure garante alta disponibilidade e resiliência das VMs.
Acordos de Nível de Serviço (SLAs): O Azure oferece SLAs que garantem um alto tempo de atividade das VMs, minimizando interrupções.

4. Segurança:
Recursos avançados de segurança: O Azure oferece recursos de segurança robustos, como criptografia de dados, firewalls e monitoramento de ameaças.
Conformidade: O Azure atende a diversos padrões de conformidade, garantindo a segurança dos dados e o cumprimento de regulamentações.

5. Facilidade de Gerenciamento:
Ferramentas de gerenciamento centralizadas: O Azure oferece ferramentas que facilitam o gerenciamento de VMs, como o Azure Portal e o Azure CLI.
Automação: É possível automatizar tarefas de gerenciamento de VMs, como implantação, dimensionamento e backup.

6. Integração com outros serviços Azure:
Ecossistema abrangente: As VMs do Azure se integram perfeitamente com outros serviços Azure, como armazenamento, bancos de dados e redes.
Desenvolvimento e teste: O Azure oferece um ambiente ideal para desenvolvimento e teste de aplicativos, com recursos para implantação e depuração.

7. Inovação:
Acesso a tecnologias de ponta: O Azure oferece acesso a tecnologias inovadoras, como inteligência artificial e aprendizado de máquina, que podem ser utilizadas em VMs.
Atualizações contínuas: A Microsoft atualiza constantemente o Azure, garantindo que as VMs tenham acesso aos recursos mais recentes.

PASSA -A -  PASSO...

# -resumo-do-lab.
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.


## 1. Acesso ao Portal do Azure:## 

Acesse o Portal do Azure (https://portal.azure.com/) utilizando sua conta Microsoft. Caso não possua uma conta, será necessário criar uma.

2. Criação do Grupo de Recursos:

Um grupo de recursos é um contêiner lógico para os recursos do Azure. Recomenda-se criar um grupo de recursos específico para sua máquina virtual.
No portal, clique em "Grupos de recursos" e, em seguida, em "Criar".
Preencha as informações necessárias:
Assinatura: Selecione sua assinatura do Azure.
Grupo de recursos: Escolha um nome para seu grupo de recursos.
Região: Selecione a região do Azure onde você deseja criar a máquina virtual.
Clique em "Examinar + criar" e, em seguida, em "Criar".

3. Criação da Máquina Virtual:

No portal, clique em "Máquinas virtuais" e, em seguida, em "Criar" e selecione "Máquina virtual do Azure".
Na página "Criar uma máquina virtual", preencha as seguintes informações:
Grupo de recursos: Selecione o grupo de recursos que você criou anteriormente.
Nome da máquina virtual: Escolha um nome para sua máquina virtual.
Região: Selecione a mesma região do grupo de recursos.
Imagem: Escolha o sistema operacional desejado (Windows Server, Linux, etc.).
Tamanho: Selecione o tamanho da máquina virtual (número de CPUs, quantidade de memória, etc.).
Conta de administrador: Defina um nome de usuário e senha para acessar a máquina virtual.
Regras de porta de entrada: Configure as portas de rede que você deseja abrir (por exemplo, porta 3389 para RDP no Windows, porta 22 para SSH no Linux).
Clique em "Disco" para configurar as opções de disco da sua máquina virtual.
Clique em "Rede" para configurar as opções de rede da sua máquina virtual.
Clique em "Gerenciamento" para configurar o monitoramento e o backup da sua máquina virtual.
Clique em "Avançado" para configurar extensões e outras opções avançadas.
Clique em "Marcas" para adicionar marcas à sua máquina virtual.
Clique em "Examinar + criar" e, em seguida, em "Criar".


4. Conexão à Máquina Virtual:

Após a criação da máquina virtual, você poderá se conectar a ela usando RDP (Windows) ou SSH (Linux).
Para se conectar via RDP, baixe o arquivo RDP no portal do Azure e execute-o.
Para se conectar via SSH, use um cliente SSH (como PuTTY) e o endereço IP da máquina virtual.

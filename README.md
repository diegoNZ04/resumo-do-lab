# resumo-do-lab

## Introdução a Computação em Nuvem
<h3>Conceitos de Nuvem</h3>
- A computação em nuvem é o fornecimento de serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis economias de escalada. 

**Nuvem Privada**
- As organizações criam um ambiente em nuvem em seu datacenter;
- As organizações são responsáveis por operar os serviços que fornecem;
- Não fornece acesso aos usuários fora da organização.

**Nuvem Pública**
- Pertencente a serviços de nuvem ou provedor de hosting;
- Fornece recursos e serviços a várias organizações e usuários;
- Acessada via conexão de rede segura (geralmente pela internet).

**Nuvem Híbrida**
- Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.
<h3>Comparação de Modelos de Nuvem</h3>

**Nuvem Pública**
- Nenhum despesa de capital para escalar verticalmente;
- Os aplicativos podem ser provisionados e desprovisionados rapidamente;
- As organizações pagam apenas pelo que utilizam.

**Nuvem Privada**
- As organizações têm controle total sobre os recursos e a segurança;
- As organizações são responsáveis pela manutenção e pelas atualizações de hardware.

**Nuvem Híbrida**
- As organizações determinam onde executar seus aplicativos;
- As organizações controlam a segurança, conformidade e os requisitos legais;
- Fornece a maior flexibilidade.
<h3>Comparação entre CapEx e OpEx</h3>
**Despesas de capital (CapEx)**
- O gasto inicial de dinheiro em infraestrutura física;
- As despesas do CapEx têm um valor que se reduz com o tempo.

**Despesas Operacionais (OpEx)**
- Gastar com produtos e serviços conforme necessário, pagamento conforme o uso;
- Seja cobrado imediatamente.

**Modelo Baseado Em Consumo**
Os provedores de serviço em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam.
- Melhor previsão de custos;
- São fornecidos preços para recursos e serviços individuais;
- A cobrança é feita um base no seu uso real.

## Benefícios da Nuvem Azure

**Alta Disponibilidade**
- A alta disponibilidade se concentra em garantir a disponibilidade de máxima, independentemente de interrupções ou eventos que possam ocorrer. 
<h3>Escalabilidade e Elasticidade</h3>

**Escalabilidade**
- A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda;
- A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda;
- O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços;
- Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa;
- Se a demanda cair, você poderá reduzir seus recursos e, assim reduzir seus custos;
- Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.

**Elasticidade**
- Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente);
- Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão;
- Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).
<h3>Confiabilidade, Previsibilidade e Segurança </h3>

**Confiabilidade**
- Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente;
- Com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo;
- Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.

**Previsibilidade**
- A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.

**Segurança**
- A nuvem oferece ferramentas de segurança que atendem ás necessidades do clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente;
- Se você quiser o controle máxima da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação patches e manutenção;
- Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
<h3>Governança e Gerenciabilidade</h3>

**Governança**
- A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação;
- Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajudam na governança e na segurança;
- Ao estabelecer uma presença de governança mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

**Gerenciabilidade**
- Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios.

*O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:*
- Escalar automaticamente a implantação de recursos com base na necessidade;
- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.

*O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:*
- Por meio de um portal da Web;
- Usando uma interface de linha comando;
- Usand APIs;
- Usando o PowerShell.

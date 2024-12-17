## Tópicos de estudos do AZ-900:

- Descrever o modelo baseado no consumo.
- Comparar os modelos de preços de nuvem.

- Termos técnicos:
    - jump service?
    - O termo "jump service" geralmente se refere a um servidor de salto (jump server ou jump host), que é um ponto de acesso intermediário em uma rede segura. Esse servidor é usado para fornecer uma camada adicional de segurança ao acessar sistemas ou redes restritas.

A computação em nuvem é o fornecimento de serviços de computação pela Internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.

- Computação
- Rede
- Armazenamento

---

## Modelos de nuvem:

- **Nuvem privada**
    - As organizações criam um ambiente em nuvem em seu datacenter.
    - As organizações são responsáveis por operar os serviços que fornecem.
    - Não fornece acesso aos usuários fora da organização.

- **Nuvem pública**
    - Pertencente a serviços de nuvem ou provedor de hosting.
    - Fornece recursos e serviços a várias organizações e usuários.
    - Acessada via conexão de rede segura (geralmente pela internet).

- **Nuvem Híbrida**
    - Combina nuvens públicas e privadas para permitir que os aplicativos sejam executados no local mais adequado.

---

## Comparação de modelos de nuvem

**Nuvem pública:**

- Nenhuma despesa de capital para escalar verticalmente.
- Os aplicativos podem ser provisionados e desprovisionados rapidamente.
- As organizações pagam apenas pelo que utilizam.

**Nuvem privada:**

- As organizações têm controle total sobre os recursos e a segurança.
- As organizações são responsáveis pela manutenção e pelas atualizações de hardware e software.

**Nuvem híbrida:**

- As organizações determinam onde executar seus aplicativos.
- As organizações controlam a segurança, a conformidade e os requisitos legais.
- Fornece a maior flexibilidade.

---

## Comparar CapEx e OpEx

**Despesas de capital (CapEx):**

- O gasto inicial de dinheiro em infraestrutura física.
- As despesas do CapEx têm um valor que se reduz com o tempo.

**Despesas operacionais (OpEx):**

- Gastar com produtos e serviços conforme necessário, pagamento conforme o uso.
- Seja cobrado imediatamente.

---

## Modelo baseado em consumo

- Os provedores de serviços em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam.
- Melhor previsão de custo
- São fornecidos preços para recursos e serviços individuais.
- A cobrança é feita com base no seu uso real.

---

## Materiais Complementares

[Apresentação do Instrutor](https://hermes.dio.me/files/assets/0353df52-12c6-404c-bc41-e711128c2732.pptx)

[Computação em nuvem](https://hermes.dio.me/files/assets/d54a774d-2403-450e-843d-700c2570aea7.pptx)

[Revisão](https://hermes.dio.me/files/assets/8b373a71-9a0d-4673-9e44-eed0d537c967.pptx)

<https://www.uvu.edu/otl/resources/group_work/pbl.html>

---

## Git e Github

1. [**Primeiros Passos com Git e Github**](https://web.dio.me/lives/primeiros-passos-com-git-e-github) *(recomendado)*
2. [*Introdução ao Git e ao GitHub*](https://web.dio.me/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9) *(opcional)*
3. [*Trabalhando com Branches no GitHub*](https://web.dio.me/course/trabalhando-com-branches-no-github/learning/32d05c5a-53b7-4f1d-a798-b9a8658240de) *(opcional)*
4. [*Git e GitHub Focado em PullRequest*](https://web.dio.me/course/git-e-github-focado-em-pullrequest/learning/7ee9e586-a200-41de-a075-fd6a7b4b5a1e) *(opcional)*

---

## Benefícios da Nuvem:

- Descrever os benefícios da alta disponibilidade e da escalabilidade na nuvem.
- Descrever os benefícios da confiabilidade e da previsibilidade na nuvem.

### Alta disponibilidade:

- A alta disponibilidade se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.

### Escalabilidade:

- A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda.
- A Capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda.
- O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços.
- Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa.
- Se a demanda cair, você poderá reduzir seus recursos e assim, reduzir seus custos.
- Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.

### Elasticidade: (Black Friday)

- Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente).
- Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão.
- Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente ( de maneira automática ou manual).

### Confiabilidade:

- Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.
- Com um design descentralizado, a nuvem permite que você tenha recurso implantados em várias regiões do mundo.

### Previsibilidade:

- A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.

### Segurança:

- A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente.
- Termo técnico Polyc ?
- Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataformas como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.

### Governança:

- A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação.
- Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
- Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

### Gerenciabilidade:

- Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambas trazem excelentes benefícios.
- O gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem. Por exemplo:
    - Escalar automaticamente a implantação de recursos com base na necessidade.
- Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
- O gerenciamento na nuvem diz respeito à maneira de gerenciar seu ambiente de nuvem e seus recursos. Por exemplo:
    - Por meio de um portal da Web;
    - Usando uma interface de linha de comando.
    - Usando APIs.
    - Usando do PowerShell.

Termo técnico: Terraform, json.

### Links:

[Benefícios da nuvem](https://hermes.dio.me/files/assets/8ac3de68-4ebd-4552-8349-41e93cb3c6e7.pptx)

[Benefícios da nuvem - Revisão](https://hermes.dio.me/files/assets/ca7236cb-ebfa-4a9a-b97c-35ae08cb27d7.pptx)

| SLA | Tempo de inatividade por semana | Tempo de inatividade por mês | Tempo de inatividade por ano |
| --- | --- | --- | --- |
| 99% | 1,68 horas | 7,2 horas | 365 dias |
| 99.9% | 10,1 minutos | 43,2 minutos | 8,76 horas |
| 99.95% | 5 munutos | 21,6 minutos | 4,38 horas |
| 99.99% | 1,01 minutos | 4,32 minutos | 52,56 minutos |
| 99.999% | 6 segundos | 25,9 segundos | 5,26 minutos |

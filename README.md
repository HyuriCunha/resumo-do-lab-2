# Resumo do Lab 2

## Benefícios da Nuvem

### 1. Alta Disponibilidade
Recursos disponíveis sempre que necessário, garantindo melhor perspectiva de continuidade.

- SLA de 99%+.
- Caso haja falha de entrega de serviço, o valor final é descontado.
- A alta disponibilidade concentra-se em garantir a máxima disponibilidade, independente de interrupções ou eventos.
- Se o tempo de inatividade ultrapassar o limite estabelecido no contrato, o cliente recebe um voucher de créditos.

### 2. Escalabilidade
Refere-se à capacidade de ajustar recursos para atender à demanda.

- Você pode adicionar mais recursos para lidar melhor com o aumento da demanda.
- O modelo de pagamento baseado em consumo permite pagar apenas pelo que é utilizado.
- Quando a demanda diminui, é possível reduzir os recursos, reduzindo os custos.

### 3. Elasticidade
A elasticidade permite que seus recursos se expandam (automaticamente ou manualmente) para lidar com picos repentinos de demanda.

- A escalabilidade pode ser feita com base em requisições.
- Adição de máquinas virtuais ou containers é possível por meio da expansão.

### 4. Confiabilidade
Devido ao design descentralizado, a nuvem oferece uma infraestrutura confiável e resiliente.

### 5. Previsibilidade
A nuvem permite avançar com confiança, tanto em termos de desempenho quanto de custo.

- Ambas as variáveis são influenciadas pelo **Microsoft Azure Well-Architected Framework**.

### 6. Segurança
A nuvem oferece diversas ferramentas de segurança que atendem às necessidades dos clientes. Contudo, muitas dessas ferramentas necessitam de implementação por parte do cliente.

- Se a aplicação de patches e manutenção for automatizada, modelos como Plataforma como Serviço (PaaS) ou Software como Serviço (SaaS) podem ser as melhores estratégias de nuvem.

### 7. Governança
Ferramentas de auditoria baseadas em nuvem ajudam a identificar recursos fora de conformidade com os padrões corporativos e fornecem estratégias de mitigação.

- Dependendo do modelo operacional, patches de software e atualizações podem ser aplicados automaticamente, o que ajuda na governança e na segurança.
- A presença de governança deve ser estabelecida o mais cedo possível para manter a nuvem atualizada, protegida e bem gerida.

### 8. Gerenciabilidade
Um dos principais benefícios da computação em nuvem é a capacidade de gerenciamento.

Exemplos de gerenciamento na nuvem:
- Escalabilidade automática dos recursos com base nas necessidades.
- Implantação de recursos a partir de modelos pré-configurados, evitando a necessidade de configuração manual.

---

## Laboratório sobre os Benefícios

### Tabela de SLA e Tempo de Inatividade Aceitável

| SLA (%)    | Tempo de Inatividade Aceitável por Semana |
|------------|-------------------------------------------|
| 99%        | 1,68 horas                                |
| 99,9%      | 10,1 minutos                              |
| 99,95%     | 5 minutos                                 |
| 99,99%     | 1,01 minuto                               |
| 99,999%    | 6 segundos                                |

Ao criar uma máquina virtual, existe a "opção de disponibilidade" para escolher o SLA desejado. Além disso, a opção de conta de armazenamento também tem impacto na redundância e no SLA.

---

Esse documento resume os benefícios essenciais da computação em nuvem e fornece uma tabela útil para referência em relação ao tempo de inatividade aceitável com base nos diferentes níveis de SLA. A partir dessa tabela, é possível entender melhor as opções de escolha de SLA e como isso impacta a disponibilidade e redundância dos serviços na nuvem.

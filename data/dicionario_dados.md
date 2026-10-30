# Dicionário de Dados

## Visão Geral

Este dicionário de dados descreve as variáveis presentes na base de clientes e pedidos, detalhando o significado de cada coluna, seu contexto de negócio e sua finalidade para análises operacionais, logísticas e de experiência do cliente.

---

## Identificação

| Campo | Descrição |
|---------|---------|
| `customer_id` | Identificador único do cliente. Utilizado para distinguir cada cliente na base de dados. |
| `order_id` | Identificador único do pedido. Permite rastrear e analisar cada transação de forma individual. |

---

## Informações do Cliente

| Campo | Descrição |
|---------|---------|
| `customer_age` | Idade do cliente em anos. |
| `customer_region` | Região geográfica onde o cliente está localizado. |
| `customer_tenure_months` | Tempo de relacionamento do cliente com a empresa, medido em meses. |

---

## Informações do Pedido

| Campo | Descrição |
|---------|---------|
| `order_value` | Valor total do pedido antes de eventuais ajustes financeiros. |
| `items_quantity` | Quantidade total de itens adquiridos no pedido. |
| `discount_value` | Valor de desconto aplicado ao pedido. |
| `payment_installments` | Número de parcelas utilizadas para pagamento do pedido. |

---

## Informações de Entrega

| Campo | Descrição |
|---------|---------|
| `delivery_time_days` | Tempo total necessário para a entrega do pedido, em dias. |
| `delivery_delay_days` | Quantidade de dias de atraso em relação ao prazo previsto de entrega. |
| `freight_value` | Valor cobrado pelo frete do pedido. |
| `delivery_attempts` | Número de tentativas realizadas para concluir a entrega do pedido. |

---

## Atendimento ao Cliente

| Campo | Descrição |
|---------|---------|
| `customer_service_contacts` | Quantidade de vezes que o cliente entrou em contato com os canais de atendimento. |
| `resolution_time_days` | Tempo necessário para resolução de problemas ou solicitações do cliente, medido em dias. |

---


# OWASPAPISecurityTop10-Mermaid
Diagramas em Mermaid envolvendo itens que integram a lista de vulnerabilidades da OWASP API Security Top 10.

## OWASP API Security Top 10 2023

Riscos que fazem parte da **OWASP Top 10 API Security Risks - 2023**:

```mermaid
block-beta
columns 1
  A["API1:2023 - Broken Object Level Authorization"]
  B["API2:2023 - Broken Authentication"]
  C["API3:2023 - Broken Object Property Level Authorization"]
  D["API4:2023 - Unrestricted Resource Consumption"]
  E["API5:2023 - Broken Function Level Authorization"]
  F["API6:2023 - Unrestricted Access to Sensitive Business Flows"]
  G["API7:2023 - Server Side Request Forgery"]
  H["API8:2023 - Security Misconfiguration"]
  I["API9:2023 - Improper Inventory Management"]
  J["API10:2023 - Unsafe Consumption of APIs"]
```

OBSERVAÇÃO: Para acessar a listagem oficial clique neste [**link**](https://owasp.org/API-Security/editions/2023/en/0x11-t10/).

### API4:2023 - Unrestricted Resource Consumption

Mindmap com recomendações e pontos importantes neste item:

```mermaid
mindmap
  root["API4:2023 - Unrestricted Resource Consumption"]
    Problemas comuns
      Item1["High CPU Usage"]
      Item2["Memory Leaks"]
      Item3["Excessive Network Bandwidth"]
    Policies
      Element1["API Rate Limiting"]
      Element2["Resource Quotas"]
      Element3["Timeouts"]
    Ferramentas
      Ferramenta1["Prometheus"]
      Ferramenta2["Grafana"]
      Ferramenta3["New Relic"]
      Ferramenta4["Application Insights"]
      Ferramenta5["Datadog"]
      Ferramenta6["Grafana"]
    API Gateways
      Gateway1["Azure API Management"]
      Gateway2["Kong"]
      Gateway3["Apigee"]
      Gateway4["Amazon API Gateway"]
      Gateway5["Ocelot"]
    Recomendações
      Recomendação1["Implementar Rate Limiting"]
      Recomendação2["Monitorar Uso de Recursos"]
      Recomendação3["Configurar Alertas de Uso Excessivo"]
      Recomendação4["Realizar Testes de Carga"]
```

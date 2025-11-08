MVP Localização de Motos — Sprint 4 (Compliance, QA & Tests)

Projeto Azure DevOps:
https://RM555656@dev.azure.com/RM555656/MVPLocaliza%C3%A7%C3%A3oDeMotos/_git/MVPLocaliza%C3%A7%C3%A3oDeMotos

Escopo da entrega
Testes manuais no nível de sistema (Azure Test Plans).
Para cada PBI que estava em progresso, foram criados e executados casos de teste cobrindo as funcionalidades principais, com dados controlados e Parameter values quando aplicável.
Evidências (prints) anexadas dentro de cada Test Case executado.
Gráficos (Charts) de Test Results by Outcome (Passed) e Test Runs by ‘Run by’ anexados ao PBI/Plano para comprovação.

PBIs cobertos na Sprint
PBI-01: Cadastrar Motocicleta
PBI-02: Indicadores do Pátio
PBI-03: Simulação de Sinal BLE
PBI-04: Preferências e Dados

Planejamento de testes
Plano: “Sprint 4 – MVP Localização”.
Organização: 1 Suite por PBI; casos com Action + Expected result detalhados.
Dados controlados: IDs únicos (ex.: moto-ABC123-0001), tempos em segundos (TTL) e valores de RSSI definidos.
Parameter values: utilizados para variar entradas sem duplicar casos (ex.: @device_id, @TTL, @rssi).

Execução e resultados
Todos os Test Cases executados foram concluídos com Expected result atingido (✔ Passed).
Não foi necessário abrir Bug: não houve divergências entre comportamento observado e critérios de aceite durante a execução dos testes planejados.
Para cada execução:
Steps marcados (Pass), com Actual result registrado quando pertinente.
Print de evidência anexado diretamente no Test Case (aba Attachments).

Evidências entreguues
Dentro dos Test Cases:
Prints da execução (um por caso) anexados.
Na PBI/Plano:
Chart — Test Results by Outcome (com destaque para Passed).
Chart — Test Runs by ‘Run by’ (histórico de execuções por executor).

# Raft
Nós participantes: Cada nó possui um estado (Follower, Candidate, ou Leader), e há um mecanismo para troca de mensagens.
Eleição: Quando o tempo de espera expira, um nó inicia uma eleição e solicita votos.
Heartbeat (batimento cardíaco): O líder envia mensagens regulares para manter os seguidores sincronizados.
Simulação de falhas: Nós podem falhar e se recuperar, afetando o processo de consenso.
Logs detalhados: As ações de cada nó são registradas no console para rastrear o comportamento.

Execute o código e observe os logs no console.
Você verá nós iniciando eleições, votando, escolhendo um líder e simulando falhas.
O líder continuará enviando heartbeats até que falhe ou seja substituído.

# Concorrência e Sincronização em Java

Projeto acadêmico desenvolvido para a disciplina de **Sistemas Operacionais**, explorando conceitos de programação concorrente e sincronização de threads.

## Experimentos

1. **Race Condition:** demonstração de condições de corrida com e sem `ReentrantLock`.
2. **Deadlock:** simulação do problema dos cinco filósofos.
3. **Aquisição Ordenada:** prevenção de deadlock por ordenação de recursos.
4. **Semáforo Garçom:** controle de concorrência utilizando `Semaphore`.

## Tecnologias
- Java (JDK 25)
- Threads
- ReentrantLock
- Semaphore

## Execução

```bash
javac SincronismoDeadlock.java
java SincronismoDeadlock
java main
```

## Objetivo

Compreender os desafios da execução concorrente, identificar problemas de sincronização e aplicar mecanismos para garantir o acesso seguro a recursos compartilhados.

**Disciplina:** Sistemas Operacionais

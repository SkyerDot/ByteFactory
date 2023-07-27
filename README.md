# ByteFactory X (Cross)
Uma modpack simples de Minecraft pra jogar com os amigos. Versão: 1.19.2

#### É recomendado usar/alocar 4GB RAM para a modpack. Valor mínimo (-Xms) e valor máximo (-Xmx) devem estar em **4096M**, ou **4G**
#### Use ``-XX:ParallelGCThreads=N`` para definir a quantidade de threads que o jogo vai usar (pesquise pelo modelo do seu processador para saber quantas threads ele tem). N = Número de threads (máx. 8)

### Argumentos JVM

```
-Xmn512m -XX:+AggressiveOpts -XX:+AlwaysPreTouch -XX:+DisableExplicitGC -XX:+ParallelRefProcEnabled -XX:+PerfDisableSharedMem -XX:-UsePerfData -XX:MaxGCPauseMillis=200 -XX:ConcGCThreads=2 -XX:+UseG1GC -XX:InitiatingHeapOccupancyPercent=50 -XX:G1HeapRegionSize=1 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=8
```

[Página no Technic](https://www.technicpack.net/modpack/bytefactory-cross.1972320)

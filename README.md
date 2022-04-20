# ByteFactory
Essa é uma modpack de Minecraft simples que eu montei para jogar com amigos. Atualmente, ela está na versão 1.12.2

#### É recomendado usar/alocar 3GB RAM para a modpack. Valor mínimo (-Xms) e valor máximo (-Xmx) devem estar em **3072M**, ou **3G**
#### Use ``-XX:ParallelGCThreads=N`` para definir a quantidade de threads que o jogo vai usar (pesquise pelo modelo do seu processador para saber quantas threads ele tem). N = Número de threads (máx. 8)

### Argumentos JVM

```
-Xmn512m -XX:+AggressiveOpts -XX:+AlwaysPreTouch -XX:+DisableExplicitGC -XX:+ParallelRefProcEnabled -XX:+PerfDisableSharedMem -XX:-UsePerfData -XX:MaxGCPauseMillis=200 -XX:ConcGCThreads=2 -XX:+UseG1GC -XX:InitiatingHeapOccupancyPercent=50 -XX:G1HeapRegionSize=1 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=8
```

### Para instalar (MultiMC):

1. Vá até a última release, clique com o botão direito em "ByteFactory.HEX.xx.MultiMC.zip" e copie o link do arquivo, ou então baixe-o normalmente.

2. No MultiMC, crie uma nova instância e escolha a opção "Importar (.zip)". 

Se você baixou, carregue o arquivo zip.
Se você copiou o link, cole-o na barra de texto ao lado do botão "Buscar"

3. Clique "OK"

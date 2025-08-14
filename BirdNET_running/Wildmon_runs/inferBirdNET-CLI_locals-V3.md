## Instalación y ambiente Python
<div>

1. Instalar [Conda](http://conda.io/)

2. Clonar el repositorio de EchoSonR
```shell
git clone https://github.com/ronaldehido/EchoSonR.git
```

3. Crear un ambiente
```shell
cd EchoSonR
conda create --name echosonr_env python=3.10
conda activate echosonr_env
```

## Ejecución BirdNET
Este es un flujo en Python para ejecutar BirdNET-CLI de forma local usando modelos personalizados y versiones originales o modificadas del analyzador
>### Running WildMon V3 in BirdNET-CLI locally
>se comparte un [cuaderno de jupyter](https://github.com/ronaldehido/EchoSonR/blob/main/BirdNET_running/Wildmon_runs/inferBirdNET-CLI_locals-V3.ipynb) que puede ejecutarse localemente (recomiendo usar Visual Studio Code)s
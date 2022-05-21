# Instalación
La instalación de Chocolatey es un proceso muy sencillo. Pero antes de poder instalarlo es necesario activar la ejecución de Scripts a través de la PowerShell.
Para ello se deben seguir estos pasos:
1. Abrir la PowerShell como Administrador. La manera más sencilla es presionar 'Windows+R', esta combinación abrirá el buscador de Windows. Una vez abierto, basta con escribir PowerShell y en vez de pulsar 'Enter' pulse 'Ctrl+Shift+Enter' y se abrirá la PwerShell como administrador.
2. Ya en la terminal escriba el comando Get-ExecutionPolicy. Este comando nos muestra el estado de la ejecución de Scripts. Si en la pantalla aparece Restricted, significa que lo tenemos bloqueado. Para activarlo ejecute este comando Set-ExecutionPolicy -ExecutionPolicy Unrestricted.
3. Ahora ya sí es posbile instalar Chocolatey. Para ello copie este script "Set-ExecutionPolicy Bypass -Scope Process -Force;
iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))". Y ejecutelo en la terminal. La instalación tardará solo unos segundos.
[EJEMPLO](https://github.com/rubenamadoc/chocolatey/blob/main/IMG/Captura%20de%20pantalla%202022-05-20%20192825.png)
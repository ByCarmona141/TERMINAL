Importar en la laptop

Ya en la nueva máquina:

Instala lo básico:
<code>
sudo apt update
sudo apt install fish git curl
</code>

Restaura configuración:
<code>
cd ~/.config
tar -xzvf fish_config_backup.tar.gz
</code>

Instala Fisher:
<code>
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher
</code>

Instala plugins automáticamente:
<code>
cat fish_plugins.txt | xargs fisher install
</code>

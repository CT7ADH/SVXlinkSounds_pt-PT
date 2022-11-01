# SVXlinkSounds_pt-PT
 Sons em Português para o SVXlink
-----------------------------------------------------------------------------
Instruçoes para actualizar:
1º
cd /usr/share/svxlink/

2º
sudo git clone https://github.com/CT7ADH/SVXlinkSounds_pt-PT.git

3º





-----------------------------------------------------------------------------
Instroçoes para criar:

<!--@CT7ADH Instrucoes finais-->
A funcionar em Debian. (Raspberry tem problemas de libs)

Instalar:

pip3 install "google-cloud-texttospeech<2.0.0"
apt-get install sox
apt-get install libsox-fmt-mp3


O script chave.json deve estar na directoria /home/pi/
O script outro.py deve estar na directoria /home/pi/

chmod +x outro.py (tornar o ficheiro executavel)
Executar:

python3 outro.py

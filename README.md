# SVXlinkSounds_pt-PT
 Sons em Português para o SVXlink
-----------------------------------------------------------------------------
Instruçoes para actualizar:

1º
<code>cd /usr/share/svxlink/</code>

2º
<code>sudo git clone https://github.com/CT7ADH/SVXlinkSounds_pt-PT.git</code>

3º





-----------------------------------------------------------------------------
Instruçoes para criar:

<!--@CT7ADH Instrucoes finais-->
A funcionar em Debian. (Raspberry tem problemas de libs)

Instalar:

<code>pip3 install "google-cloud-texttospeech<2.0.0"</code>
<code>apt-get install sox</code>
<code>apt-get install libsox-fmt-mp3</code>


O script chave.json deve estar na directoria /home/pi/
O script outro.py deve estar na directoria /home/pi/

<code>chmod +x outro.py (tornar o ficheiro executavel)</code>
Executar:

<code>python3 outro.py</code>

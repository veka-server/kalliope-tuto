## -- EN COURS DE REDACTION --

# kalliope-tuto
tuto d'installation de kalliope

pour voir la documentation officiel : https://kalliope-project.github.io/kalliope/installation/debian/

# Pré-requis
```bash
sudo apt-get update && apt-get install -y \
    git python3-dev libpython3-dev libsmpeg0 libttspico-utils libsmpeg0 flac \
    libffi-dev libffi-dev libssl-dev portaudio19-dev build-essential \
    libatlas3-base mplayer wget vim sudo locales \
    python3-distutils pulseaudio-utils libasound2-plugins python3-pyaudio libasound-dev \
    libportaudio2 libportaudiocpp0 ffmpeg mplayer \
    
sudo wget https://bootstrap.pypa.io/get-pip.py && python3 get-pip.py    
```

# Installation
```bash
sudo pip3 install kalliope
```

# Preparation des dossiers
Il faut creer les dossier qui contiendrons les modules à installer ainsi que les fichiers de config.
```bash
git clone https://github.com/kalliope-project/kalliope_starter_fr.git /etc/kalliope
```
Vous pouvez a present utiliser le dossier /etc/kalliope pour editez les fichiers de config

# Mise a jour
```bash
pip3 install --upgrade kalliope
```

# Desinstallation
```bash
sudo pip3 uninstall kalliope
sudo rm -R /etc/kalliope
```

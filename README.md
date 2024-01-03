# CutiePi stage for building image using pi-gen  
  
Usage:  
    git clone https://github.com/lipschitzallee/pi-gen_stage4.5-cutiepi  
    cd pi-gen_stage4.5-cutiepi  
    git clone https://github.com/RPi-Distro/pi-gen -b arm64  
    cp stage4.5-cutiepi config -a pi-gen/  
    cd pi-gen/  
    vim config  
    sudo ./build.sh   

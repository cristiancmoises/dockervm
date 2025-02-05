# DOCKERVM
[![DOI](https://zenodo.org/badge/661488540.svg)](https://doi.org/10.5281/zenodo.14810062)

Just some docker commands to use docker like VmWare/Virtualbox

![image](https://github.com/cristiancmoises/dockervm/assets/86272521/ab87b45c-4139-4f58-b0da-04811fba3a46)

# ACCESS THE SYSTEM IN THE CONTAINER
       docker run -it IMAGE_ID_HERE /bin/bash
# START ALL STOPPED CONTAINERS
       docker start $(docker ps -a -q --filter "status=exited")
# RUN THE LAST STOPPED CONTAINER:
       docker start -a -i 'docker ps -q -l'
# LIST ALL IMAGES
       docker images
# LIST ALL CONTAINERS
       docker ps -a
# RE-ACCESS THE SYSTEMS
       docker exec -it CONTAINER_ID_HERE /bin/bash
       
# 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=cristiancmoises/dockervm&type=Date)](https://star-history.com/#cristiancmoises/dockervm&Date)

# Dockerfile for LDSC (LD SCore) (https://github.com/bulik/ldsc)
  - To start the container:
  ```
  docker run -i -t -v PathToYourData:/data zijingliu/ldsc /bin/bash
  ```
  - After running the container, ldsc is in the `/ldsc` folder
  ```
  cd ldsc
  ./ldsc.py -h
  ```
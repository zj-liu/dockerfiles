# Dockerfile for SLDP (Signed LD Profile) regression (https://github.com/yakirr/sldp)
  - To start the container:
  ```
  docker run -i -t -v PathToYourData:/data zijingliu/sldp /bin/bash
  ```
  - sldp is in the system path. After running the container, you can run 
  ```
  sldp -h
  ```
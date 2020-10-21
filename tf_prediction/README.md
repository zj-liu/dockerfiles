# Dockerfile to run the prediction of transcription factor binding with deep learning 
  - To start the container:
  ```
  docker run -i -t -v PathToYourData:/data zijingliu/tf_prediction /bin/bash
  ```
  - After running the container, you got the Anaconda environment ready to run the prediction of transcription factor binding.

  - Example to use in Singularity
  ```
  singularity exec --nv docker://zijingliu/tf_prediction:latest YOUR_COMMANDS
  ```
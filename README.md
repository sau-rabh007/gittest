version 0.2
  phases:
    install:
      command:
        -javac ready.java
        -java sum
      finally:
        -echo Executing Install phase
    pre_build:
      command:
         -echo entering pre build phase
    build:
      command:
        -echo enter ing the build step
    post_build:
      command:
        -echo completed with build
            
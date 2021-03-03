# docker-app-webfluids on Windows

WebGL Fluids - Docker App (2021)

From original: https://paveldogreat.github.io/WebGL-Fluid-Simulation/


## Download the code and Build the container (on PowerShell)
> git clone https://github.com/Juli-BCN/webfluids-docker-windows.git

> cd webfluids-docker-windows

> docker build -t webfluids-win .

> docker images



## Run, Test & Stop the Docker container
> docker run -it -p 80:80 docker-webfluids

> curl -L http://localhost

> docker ps

> :eyeglasses: docker stop *CONTAINER_ID*
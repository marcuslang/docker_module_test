1.  preparation
start docker toolbox

2. CMD
docker-machine env --shell cmd default

3. CMD
@FOR /f "tokens=*" %i IN ('docker-machine env --shell cmd default') DO @%i

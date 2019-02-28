FROM ubuntu

RUN apt update && apt upgrade -y

CMD exec /bin/bash -c "trap : TERM INT; sleep infinity & wait"
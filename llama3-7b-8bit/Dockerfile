FROM pytorch/pytorch:2.3.0-cuda12.1-cudnn8-devel

RUN apt update
RUN apt upgrade -y
RUN apt install git -y
RUN apt install git-lfs -y

WORKDIR /app

RUN python3 -m pip install "unsloth[cu121-ampere-torch230] @ git+https://github.com/unslothai/unsloth.git"

COPY ./llama_3_8b_unsloth_niv-al_instruct.py ./llama_3_8b_unsloth_niv-al_instruct.py

CMD ["python3", "llama_3_8b_unsloth_niv-al_instruct.py"]

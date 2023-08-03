FROM nvidia/cuda:11.8.0-cudnn8-devel-ubuntu22.04

ENV DEBIAN_FRONTEND noninteractive


RUN apt-get update -y && \
    apt-get upgrade -y && \
    apt-get install -y sudo && \
    apt-get install -y python3-pip

RUN apt-get install -y curl wget htop sudo git git-lfs software-properties-common build-essential libgl1 unzip trash-cli

RUN pip install --upgrade pip

RUN pip install --no-cache-dir torch torchvision torchaudio numpy pandas seaborn matplotlib transformers datasets


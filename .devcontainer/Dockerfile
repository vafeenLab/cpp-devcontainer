# Используем официальный образ GCC
FROM gcc:latest

# Устанавливаем инструменты
RUN apt-get update && apt-get install -y \
    cmake \
    make \
    gdb \
    && rm -rf /var/lib/apt/lists/*

# Рабочая директория — будет перекрыта монтированием
WORKDIR /workspace

FROM archlinux:latest

RUN pacman -Syu --noconfirm

RUN pacman -S go --noconfirm

WORKDIR /home

COPY . .

RUN go build -o hw hello-world.go

CMD ["./hw"]

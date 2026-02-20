FROM gcc:12

RUN apt-get update && apt-get install -y g++

WORKDIR /app

COPY app.cpp .

RUN g++ app.cpp -o app

EXPOSE 8080

CMD ["./app"]

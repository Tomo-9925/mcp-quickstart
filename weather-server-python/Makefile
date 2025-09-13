build:
	sudo docker buildx build -t tomo-9925/weather-server:latest .

run:
	sudo docker run -d --rm --name weather-server -p 8000:8000 tomo-9925/weather-server:latest

stop:
	sudo docker stop weather-server

clean:
	sudo docker buildx prune
	sudo docker images rm tomo-9925/weather-server

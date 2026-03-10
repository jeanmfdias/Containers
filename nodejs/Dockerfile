FROM nginx:1.27

RUN apt-get update && apt-get upgrade -y && \
	apt-get install -y curl git && \
	curl -fsSL https://deb.nodesource.com/setup_22.x | bash - && \
	apt-get install -y nodejs && \
	npm install -g yarn && \
	rm -rf /var/lib/apt/lists/*

EXPOSE 3000
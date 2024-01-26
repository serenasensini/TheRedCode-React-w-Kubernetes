# React on Kubernetes

## Iniziamo!

### Docker

Clona il repo e apri il terminale all'interno della cartella.

Lancia il comando:

`docker build -t my-react .
docker run -p 3000:3000 my-react`

Apri il browser all'indirizzo _http://localhost:3000_, et voilà!

### Kubernetes

Clona il repo e apri il terminale all'interno della cartella.

Lancia il comando:

`kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
`

Apri il browser all'indirizzo _http://localhost:3000_, et voilà!

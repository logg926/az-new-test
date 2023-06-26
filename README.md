pip install -r requirements.txt


uvicorn main:app --reload


docker build -t logg926/my-fastapi-app:1.0 .

docker push logg926/my-fastapi-app:1.0

kubectl apply -f deployment.yaml
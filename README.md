## Multicontainer dapr example from [Get started with Dapr](https://docs.microsoft.com/en-us/dotnet/architecture/dapr-for-net-developers/getting-started)

## Deploy to local kubernetes (Docker desktop)
Just isuue apply specifying the deploy folder,
```
kubectl apply -f ./deploy
```
## Viewing frontend
Go to http://localhost:80 to view the frontend weather data.

## Shut down the deployment
Just isuue delete specifying the deploy folder,
```
kubectl delete -f ./deploy
```

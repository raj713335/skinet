# skinet
### 1. Clone the Repository:
```
git clone https://github.com/raj713335/skinet
```

### 2. Run the .NET(5.0) Backend Application:

## Running the Redis Server

```
cd skinet
docker-compose up --detach
```

```
dotnet tool install --global dotnet-ef --version 6.0.8
```

## Installing the Dot Net Tools

```
dotnet tool install --global dotnet-ef --version 6.0.8
```

## Dropping and running the SQLite Database

```
cd skinet
dotnet ef database drop -p Infrastructure -s API -c StoreContext
```

```
cd skinet
dotnet clean
dotnet build skinet.sln
cd API
dotnet watch run --skinet
```

## Runiing EF Migration (Code First Approach)

```
dotnet ef migrations add OrderEntityAdded -p Infrastructure -s API -c StoreContext
```

### 3. Run the Angular(11.2.1) Frontend Application:

```
cd skinet/client
npm install
ng serve
```

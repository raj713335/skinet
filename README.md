# skinet
### 1. Clone the Repository:
```
git clone https://github.com/raj713335/skinet
```

### 2. Run the .NET(5.0) Backend Application:

## Installing the Dot Net Tools

```
dotnet tool install --global dotnet-ef --version 6.0.8
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

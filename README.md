# aircnc

Omnistack 09

## Frontend

![frontend-screenshot01](screenshots/frontend-screenshot01.png)

![frontend-screenshot02](screenshots/frontend-screenshot02.png)

![frontend-screenshot03](screenshots/frontend-screenshot03.png)

## Mobile

![mobile](screenshots/mobile.png)

## Steps to Setup

1. Clone this repository

```bash
git clone https://github.com/MarioCesarJr/aircnc.git
```

2. Connect application with MongoDB Atlas

```bash
cd backend
```

Open `src/server.js` file and edit:

```
mongoose.connect(
  'mongodb+srv://<username>:<password>@cluster0-xyulq.mongodb.net/semana09?retryWrites=true&w=majority',
  {
    useNewUrlParser: true,
    useUnifiedTopology: true
  }
);
```

3. Install dependencies

```bash
> yarn
```

4. Run api

```bash
> yarn dev
```

## Frontend

1. Install dependencies

```bash
> cd frontend
```

```bash
> yarn
```

2. Run App

```bash
> yarn start
```

Open <http://localhost:3000> to view it in the browser.

## Mobile - Made with Expo

1. Install dependencies

```bash
> cd mobile
```

```bash
> yarn
```

2. Run app

```bash
> yarn start
```

3. Choose device

```bash
  # android
> Run on Android device/emulator

  # ios:
> Run on iOS emulator
```


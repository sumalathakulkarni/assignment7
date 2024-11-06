## Create Virtual Environment

```sh
virtualenv assignment7
```

## Activate Virtual Environment

```sh
source assignment7/bin/activate
```

## Install Packages

```sh
pip install -r requirements.txt
```

## Build Image Command 

```sh
docker build -t my-qr-app .
```

## Running the Container App

```sh
docker run -d --name qr-generator my-qr-app
```

## Generate QR Code

```sh
docker run -v .:/app qrcode --url https://github.com/sumalathakulkarni/assignment7
```


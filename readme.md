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

## Command for generating the QR Code

```sh
docker run -v .:/app qrcode --url https://github.com/sumalathakulkarni/
```
![image](https://github.com/user-attachments/assets/0177ca19-6dbf-461f-a3ad-7db2839e2e19)

## Generated QR Code
![image](https://github.com/user-attachments/assets/df2c5b54-781f-406d-b6a3-42c3f6b38952)

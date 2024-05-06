<h3 align="center">Өгөгдлийн шинжилгээ болон Инженэрчлэлийн оновчлолын бие даалт болох 
DATA Science AI automatic service SERVICE</h3>

---
<h5 align+center">Streamlit file луу орж ажиллууна бусад directory-г битгий оролдоорой </h5>


<h5 align="center">WARNING</p>
<p align="center"> run command streamlit run <filename>.py</p>
<p align="center"> GOLANG next js python streamlit.
    <br> 
</p>

## 📝 Агуулга

- [Систем](#about)
- [Шаардлага](#getting_started)
- [Ажлуулах](#run)
- [Сервер](#deployment)
- [Ашигласан технологи](#built_using)

## 🧐 Систем <a name = "about"></a>

DATA Science AI automatic service SERVICE

## 🏁 Шаардлага <a name = "getting_started"></a>

Үйлдлийн систем дээр дараах зүйлсийг суулгасан байх шаардлагатай.

> Linux болон macOS систем дээр суулгах зааврууд.

#### SQLC

Sqlc нь SQL-ээс golang код үүсгэхэд ашиглана.

<details>
<summary>sqlc суулгах</summary>

#### MacOS

```sh
brew install sqlc
```

#### Linux

```sh
go install github.com/sqlc-dev/sqlc/cmd/sqlc@latest
```

</details>

#### PROTOC

Protocol buffer хөрвүүлэгч, protoc нь .proto файлуудыг complile хийхэд ашиглана.

<details>
<summary>protoc суулгах</summary>

#### Linux ubuntu

```sh
 apt install -y protobuf-compiler
```

#### MacOS

```sh
 brew install protobuf
```

#### Linux bin

```sh
PB_REL="https://github.com/protocolbuffers/protobuf/releases"
```

```sh
curl -LO $PB_REL/download/v{{< param protoc-version >}}/protoc-{{< param protoc-version >}}-linux-x86_64.zip
```

```sh
unzip protoc-{{< param protoc-version >}}-linux-x86_64.zip -d $HOME/.local
```

```sh
export PATH="$PATH:$HOME/.local/bin"
```

</details>

#### PROTOLINT

.proto файлуудын lint.

<details>
<summary>protolint суулгах</summary>

#### Linux

```sh
go install github.com/yoheimuta/protolint/cmd/protolint@latest
```

#### MacOS

```sh
brew install protolint
```

</details>

#### GOLANGCI-LINT

.go файлууд буюу golang lint.

<details>
<summary>golangci-lint суулгах</summary>

#### Linux

```sh
curl -sSfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh | sh -s -- -b $(go env GOPATH)/bin v1.55.2
```

#### MacOS

```sh
brew install golangci-lint
```

</details>

## 🗒️ VSCode тохиргоо <a name = "vscode"></a>

Дараах тохиргоо нь vscode дотор golangci lint ашиглахад хэрэгтэй.

#### Settings.json

```json
"go.lintFlags": ["--fast"],
"go.lintTool": "golangci-lint",
```

#### Extensions

- [Protolint](https://marketplace.visualstudio.com/items?itemName=Plex.vscode-protolint)
- [SQL Formatter](https://marketplace.visualstudio.com/items?itemName=adpyke.vscode-sql-formatter)
- [Proto 3](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3)

## 🔧 Ажлуулах <a name = "run"></a>

#### 1. Програмыг хэрхэн ажиллуулах тухай.

```
pip install streamlit 
болон шаардлагатай хэсэг бүлэг санг суулгах ёстой
```

```
streamlit run <filename>.py
```

```
streamlit run <filename>.py
    └── nextjs ---> read config ---> firebase config ----> read kuble golang backend
          └── golang make sqlc grpc turning on byte working kuble 
```

## 🚀 Сервер <a name = "deployment"></a>


- CI/CD github self hosted action ашиглаж байгаа учир runner server дээр ажиллаж байх ёстой.

- Kubernetes server дээр Deployment болон Service-ийг yaml дээр бичнэ.
- Kubernetes server дээр Deployment хийхээс гадна AWS дээр сервер асааж byte болгон python file дотор оруулсан тул python streamlit directory-гоос бусад directory луу битгий ор
## ⛏️ Ашигласан технологи <a name = "built_using"></a>

- [sqlc](https://github.com/sqlc-dev/sqlc)
- [grpc](https://github.com/grpc/grpc)
- [rabbitmq](https://github.com/wagslane/go-rabbitmq)
- [golang-migrate](https://github.com/golang-migrate/migrate)
- [pgx](https://github.com/jackc/pgx)
- [python](https://www.python.org/)
- [nextjs](https://www.nextjs.org)
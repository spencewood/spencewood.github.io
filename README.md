## Setup

```shell
git clone -b source git@github.com:tcollard/tcollard.github.io.git
cd tcollard.github.io
mkdir deploy && cd deploy
git init .
git remote add origin git@github.com:tcollard/tcollard.github.io.git
```

## New Post

```shell
rake post
```

## Deploy

```shell
rake deploy
```
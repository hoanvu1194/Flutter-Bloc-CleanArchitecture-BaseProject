### Getting Started

### Requirements

- Dart: 2.18.5
- Flutter SDK: 3.3.9
- Melos: 2.8.0
- CocoaPods: 1.11.2

### Install

- WARN: If you already installed `melos` and `lefthook`, you could omit this step.

- Install melos:
    - Run `dart pub global activate melos 2.8.0`

- Install lefthook (optional):
    - Run `gem install lefthook`

- Export paths:
    - Add to `.zshrc` or `.bashrc` file
```    
export PATH="$PATH:<path to flutter>/flutter/bin"
export PATH="$PATH:<path to flutter>/flutter/bin/cache/dart-sdk/bin"
export PATH="$PATH:~/.pub-cache/bin"
export PATH="$PATH:~/.gem/gems/lefthook-0.7.7/bin"
```
    - Save file `.zshrc`
    - Run `source ~/.zshrc`

### Config and run app

- cd to root folder of project
- Run `make gen_env`
- Run `make sync`
- Run `lefthook install` (optional)
- Run & Enjoy!

## Upgrade Flutter
- Update Flutter version in:
    - [README.md](#requirements)
    - [bitbucket-pipelines.yml](bitbucket-pipelines.yml)
    - [ci.yaml](.github/workflows/ci.yaml)
    - [cd_develop.yaml](.github/workflows/cd_develop.yaml)
    - [cd_qa.yaml](.github/workflows/cd_qa.yaml)
    - [cd_staging.yaml](.github/workflows/cd_staging.yaml)
    - [cd_production.yaml](.github/workflows/cd_production.yaml)

## Upgrade Melos
- Update Melos version in:
    - [README.md](#requirements)
    - [Install](#install)
    - [bitbucket-pipelines.yml](bitbucket-pipelines.yml)
    - [ci.yaml](.github/workflows/ci.yaml)
    - [cd_develop.yaml](.github/workflows/cd_develop.yaml)
    - [cd_qa.yaml](.github/workflows/cd_qa.yaml)
    - [cd_staging.yaml](.github/workflows/cd_staging.yaml)
    - [cd_production.yaml](.github/workflows/cd_production.yaml)

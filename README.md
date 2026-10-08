# Introduction

이 organization (Nonperturbative-QCD-theory-group)은 해당 연구실과 관련된 Github 기능을 연구실 참여인원에게 제공하기 위하여 만들어진 기능이다.

# Features

## 1. Claude 기능 확장

이 organization은 무료로 이용 가능한 Claude Team plan을 운영 중이다. Claude Team plan에서 skill을 사용하기 위해서는 Antropic이 자체적으로 제공하는 skill을 추가하거나 외부에서 제공하는 skill을 추가하여야 한다. 
외부에서 제공하는 skill을 추가하기 위해서는, 먼저 해당 skill을 제공하는 MCP 혹은 Marketplace의 repository를 fork하여 private repository를 생성한 후, Claude Team plan의 설정에서 추가하여야 한다.
이 organization은 Team plan에 사용할 외부 skill을 추가하기 위한 github 공간을 제공한다. 다음은 외부 skill을 Team plan에 추가하는 방법이다:

1. 추가하고 싶은 외부 skill에 포함된 repository를 찾는다.
2. 그 repository를 이 organization 권한으로 fork한다.
     - 이 단계는 organization에 참가한 인원들의 개인 계정으로도 가능하다.
4. Repository 설정에서 해당 repository를 **Unfork->Archive->Private->Unarchive**하여 fork되지 않은 private repository로 만든다.
     - Fork된 repository는 private할 수 없고, Claude에 skill을 추가하기 위해서는 repository가 private하여야 하기 때문이다.
5. Claude 설정에 들어가 skill을 추가한다.
     - 이 단계는 Claude Team plan 관계자만 가능한 것으로 파악되나, 관리자가 아닌 인원이 skill 추가를 요청할 수 있을 것으로 예상된다.
6. Team 단위로 추가된 skill을 개인 계정에서 활성화하여 사용한다.

## 2. 추가 바람

# 추가 바람

   

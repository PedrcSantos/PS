

# Corporate Collaboration

Corporate Collaboration é uma plataforma colaborativa para facilitar e agilizar a gestão de necessidades internas das empresas.


## Requisitos

- [_OutSystems Service Studio 11_](https://www.outsystems.com/downloads/)

Para além do referido, é também necessário ter uma conta Google de modo a obter uma chave que permite o uso do Google Maps JavaScript API bem como Places API.
- Ver como obter a [_API key_](https://developers.google.com/maps/documentation/javascript/get-api-key).

---

## Instalação

Uma vez concluída a instalação do [_OutSystems Service Studio 11_](#Requisitos)

Na pasta Projecto/ encontram-se os projetos OutSystems (ficheiros _.oml_) dos módulos utilizados, dividos nas pastas _frontend_ e _backend_ no desenvolvimento da aplicação. 
O módulo principal é o UserEndPoints através do qual deve iniciar a aplicação. 

Para analisar o código e verificar os módulos constituintes do projeto, para cada módulo abrir o seu ficheiro _.oml_, com o _OutSystems Studio 11_.

Para correr a aplicação de imediato, abrir o ficheiro CollaborationPlatform.oap com o _OutSystems Studio 11_


**NOTA**

No módulo UserEndPoints, de modo a poder utilizar o _Google Maps_, é necessário associar uma _API Key_. Para tal no ecrã NecessityCreation, na _client action_ _OnReady_ alterar a chave.

---

## Utilização

Para utilizar a aplicação, apenas é necessário aceder ao URL 
- https://grupo-ps.outsystemscloud.com/UserEndPoints/

Para efeitos de visualização ou modificação do código revisitar a secção [como instalar](#Instalação).

---

## Utilizadores gerais
As credenciais listadas seguem o formato.
- UserName:
    - Password

Utilizadores:

- Admin: 
    - collaborationPLATFORM
- RegularUser:
    - COLLABORATIONplatform

**NOTA**

As credenciais acima existem apenas para utilizadores do _endpoint_:

- https://grupo-ps.outsystemscloud.com/UserEndPoints/

Caso importar os ficheiros .oml pode criar utilizadores no _endpoint_
 - https:://YOUR-ENVIRONMENT/Users

---
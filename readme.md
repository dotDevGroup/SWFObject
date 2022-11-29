<div align="center">
    <img src="https://raw.githubusercontent.com/dotDevGroup/SWFObject/main/images/header.gif"/>
</div>

## Suporte Multilíngue
Este repositório foi marcado pela [dotDev](https://github.com/dotDevGroup) como um *repositório multilíngue*. Isto implica que ele trabalhará com base em duas ou mais línguas, das quais poderão ser adicionadas com o tempo. Atualmente, o repositório do SWFObject e sua Wiki estão disponíveis em dois idiomas além do **Português Brasileiro**: **Inglês** e **Espanhol**. 

#### English Translation
This repository was signed by [dotDev](https://github.com/dotDevGroup) as a *multilanguage repository*. That implies that it will work based on two or more languages, which may be added over time. Currently, the SWFObject repository and its Wiki are available in two languages besides **English**: **Brazilian Portuguese** and **Spanish**.

#### Traducción Española
Este repositorio ha sido marcado por [dotDev](https://github.com/dotDevGroup) como un *repositorio multilingüe*. Esto implica que funcionará en base a dos o más idiomas, los cuales podrán ser agregados con el tiempo. Actualmente, el repositorio SWFObject y su Wiki están disponibles en dos idiomas además del **Español**: **Inglés** y **Portugués Brasileño**.

## Por que retornar com o SWFObject?
Após mais de oito anos sem notícias do repositório oficial, começamos a perceber que o SWFObject, ainda utilizado em muitos projetos de Habbo Retrô anda defasado e **com diversos problemas que tocam à respeito da segurança**. Tendo isso em mente, e tendo muita noção que muitas pessoas ainda utilizam do **Adobe Flash Player** em algumas de suas atividades na internet, resolvemos atualizar o repositório, refatorando-o para uma versão mais atualizada e que consiga renderizar objetos com mais facilidade e velocidade. Notamos que o principal recurso, e que renderiza os elementos **DOM** do *Flash* está extremamente defasado, o **ActiveXObject**, originalmente utilizado como implementação no **IE+5.5**.

#### English Translation
After more than eight years without news from the official repository, we started to realize that SWFObject, still used in many Habbo Retro projects, is out of date and **has several security issues**. Bearing this in mind, and being very aware that many people still use **Adobe Flash Player** in some of their activities on the internet, we decided to update the repository, refactoring it to a more up-to-date version that can render objects with more ease and speed. We noticed that the main feature that renders the **DOM** elements of *Flash* is extremely outdated, the **ActiveXObject**, originally used as an implementation in **IE+5.5**.

#### Traducción Española
Después de más de ocho años sin noticias del repositorio oficial, empezamos a darnos cuenta de que SWFObject, que aún se usa en muchos proyectos de Habbo Retro, está desactualizado y **con varios problemas que tocan la seguridad**. Teniendo esto en cuenta, y siendo muy conscientes de que muchas personas todavía usan **Adobe Flash Player** en algunas de sus actividades en Internet, decidimos actualizar el repositorio, refactorizándolo a una versión más actualizada que puede representar objetos con más facilidad y rapidez. Nos dimos cuenta de que el recurso principal, que representa los elementos DOM de Flash, está extremadamente desactualizado, el ActiveXObject, originalmente utilizado como una implementación en **IE+5.5**.

### O que podemos esperar do novo SWFObject?
Um sistema criptográfico para proteger as suas *variáveis* sem conflitos com o **JavaScript** ou o **PHP**; linguagem utilizada na maior parte dos sites que ainda utilizam do *Flash* retroativamente. Todas as requisições externas seguirão à risca o protocolo ``https``, garantindo criptografia de ponta a ponta, ao passo em que mantém todos os dados sensíveis de seu projeto seguros. 

#### English Translation
A cryptographic system to protect your *variables* without conflicts with **JavaScript** or **PHP**; language used on most sites that still use *Flash* retroactively. All external requests will strictly follow the ``https`` protocol, ensuring end-to-end encryption, while keeping all sensitive data in your project safe.

#### Traducción Española
Un sistema criptográfico para proteger tus *variables* sin conflictos con **JavaScript** o **PHP**; idioma utilizado en la mayoría de los sitios que todavía usan *Flash* retroactivamente. Todas las solicitudes externas seguirán estrictamente el protocolo ``https``, lo que garantiza el cifrado de extremo a extremo y mantiene seguros todos los datos confidenciales de su proyecto.

#### **SWFObject** ``2.3.20130521``
```javascript
var flashvars = {
  "client.allow.cross.domain": "1",
  "client.notify.cross.domain": "0",
  "site.url": "value",
  "use.sso.ticket": "1",
  "sso.ticket": "value",
  "processlog.enabled": "1",
  "flash.client.origin": "popup",
  "connection.server": "value",
  "external.client": "false"
};
```
#### **SWFObject** ``3.0.0`` (e.g.)
```javascript
var flashvars = ewogICJjbGllbnQuYWxsb3cuY3Jvc3MuZG9tYWluIjogIjEiLAogICJjbGllbnQubm90aWZ5LmNyb3NzLmRvbWFpbiI6ICIwIiwKICAic2l0ZS51cmwiOiAidmFsdWUiLAogICJ1c2Uuc3NvLnRpY2tldCI6ICIxIiwKICAic3NvLnRpY2tldCI6ICJ2YWx1ZSIsCiAgInByb2Nlc3Nsb2cuZW5hYmxlZCI6ICIxIiwKICAiZmxhc2guY2xpZW50Lm9yaWdpbiI6ICJwb3B1cCIsCiAgImNvbm5lY3Rpb24uc2VydmVyIjogInZhbHVlIiwKICAiZXh0ZXJuYWwuY2xpZW50IjogImZhbHNlIgp9;
```

## Coletânea Adobe Flash Player 2022
A coletânea **Adobe Flash Player 2022** contra com outros repositórios que são úteis para manutenção de um ambiente Flash neste ano. Com o **Apache Flex** cortando as ferramentas principais, resolvemos juntar todas as informações sobre a linguagem em vários repositórios, que serão atualizados conforme houverem mais avanços em adquirir as antigas ferramentas novamente. Eles podem ser conferidos abaixo.

#### English Translation

#### Traducción Española

### Links
1. [ClothingBuilder](https://github.com/dotDevGroup/ClothingBuilder) (Apache Flex)  
2. [FurniBuilder](https://github.com/dotDevGroup/FurniBuilder) (Apache Flex)  
3. [SWFObject Wiki](https://github.com/dotDevGroup/SWFObject/wiki) (ActionScript)

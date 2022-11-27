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
Após mais de oito anos sem notícias do repositório oficial, começamos a perceber que o SWFObject, ainda utilizado em muitos projetos de Habbos Retrô anda defasado e **com diversos problemas que tocam à respeito da segurança**. Tendo isso em mente, e tendo muita noção que muitas pessoas ainda utilizam do **Adobe Flash Player** em algumas de suas atividades na internet, resolvemos atualizar o repositório, refatorando-o para uma versão mais atualizada e que consiga renderizar objetos com mais facilidade e velocidade. Notamos que o principal recurso, e que renderiza os elementos **DOM** do *Flash* está extremamente defasado, o **ActiveXObject**, originalmente utilizado como implementação no **IE+5.5**.

#### English Translation


#### Traducción Española

### O que podemos esperar do novo SWFObject?
Um sistema criptográfico para proteger as suas *variáveis* sem conflitos com o **JavaScript** ou o **PHP**; linguagem utilizada na maior parte dos sites que ainda utilizam do *Flash* retroativamente. Todas as requisições externas seguirão à risca o protocolo ``https``, garantindo criptografia de ponta a ponta, ao passo em que mantém todos os dados sensíveis de seu projeto seguros. 

#### English Translation


#### Traducción Española

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

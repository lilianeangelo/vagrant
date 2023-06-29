# vagrant
O Vagrant é uma ferramenta de código aberto que permite criar e gerenciar ambientes de desenvolvimento virtualizados de forma fácil e automatizada. Ele fornece uma camada de abstração sobre diferentes tecnologias de virtualização, como VirtualBox, VMware e Hyper-V, permitindo que desenvolvedores criem e compartilhem ambientes de desenvolvimento consistentes e reproduzíveis.

## Pré-Requisitos
* O que você precisa para executar o Vagrant:
  - Baixe um Hypervisor a seu gosto para que possa executá-lo numa máquina virtual (no caso estarei utilizando [Virtual Box](https://www.virtualbox.org/)).
    Ele será responsável por criar e gerenciar suas máquinas virtuais;
  - Baixe o [Vagrant](https://developer.hashicorp.com/vagrant/downloads) no sistema operacional host, ou seja, na máquina que você criou por meio do seu hypervisor;
  - Baixe uma [Box](https://app.vagrantup.com/boxes/search) apropriada ao seu ambiente de desenvolvimento;

**Instruções:** 
```
# verificar versão
vagrant --version

# Para instalar o plugin
vagrant plugin install vagrant vb-guest --<plugin_version>
```    

## Comece por aqui ;)
O lab proposto abaixo sobe um Apache, nada mais nada menos que um servidor web mais popular no mundo que garante um ambiente robusto e seguro para hospedar sites e aplicações web.
Ele atua como o intermediário entre o cliente (navegador da internet) e o servidor (onde o aplicativo está hospedado).
Mais informações você encontra em [Apache Foundation](https://www.apache.org/).

```
```


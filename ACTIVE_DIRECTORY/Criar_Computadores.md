# Criar Computadores

🔹 Crie uma VM (Windows)

## **Configure um IP estático:**

🔹Windows + R > digite ncpa.cpl

🔹Botão direito no Ethernet > Propriedades

🔹Selecione Internet Protocol Version 4 (IPv4) > Propriedades

🔹Selecione: Use the following IP address

🔹Entre o IP estático (ex: 192.168.1.103)

🔹Subnet Mask 255.255.255.0

🔹Default Gateway (ex: 192.168.1.1)

🔹DNS Server = Mesmo IP do Domain Controller

🔹OK

## **Mude o nome da máquina:**

🔹Windows + R > sysdm.cpl

🔹Aba Computer Name > Change

🔹OK

🔹Restart the system

## **Insira a máquina no domínio** 

🔹Windows + R > sysdm.cpl

🔹Aba Computer Name > Change

🔹Selecione Domain

🔹Entre o nome > OK

🔹Entre username: ex: LAB\Administrator

🔹Entre password: (senha do servidor)

🔹OK

🔹Aparecerá a mensagem: “Welcome to the lab.local domain”

🔹OK

🔹Reinicie a máquina

🔹Faça o login com usuário e senha sob o domínio criado

🔹Abra o CMD e rode o comando "whoami" para conferir se está no domínio.

# ansible-pipeline
Desplegué infraestructura en Azure utilizando Terraform, configurando recursos como máquinas virtuales, redes y almacenamiento. Para ello, autenticé mi cuenta en Azure, inicialicé Terraform, definí los archivos de configuración (main.tf, variables.tf, providers.tf), ejecuté terraform apply para crear los recursos y verifiqué su implementación.
![Captura de pantalla 2025-04-01 195500](https://github.com/user-attachments/assets/79276109-64fa-4716-8c21-9e9c50c29446)
```bash
 terraform init
```
```bash
 terraform plan

```
```bash
 terraform apply

```

##Run playbook
```bash
 ansible-playbook -i inventory.ini playbook.yml
```
![Captura de pantalla 2025-04-01 212606](https://github.com/user-attachments/assets/022669bc-462b-42fd-a6e5-7d83efa1c490)

##Configurando jenkins 
* instalar los complementos : SSH Build Agents: To add the agent in Jenkins y GitHub Plugin: To clone and use the project repository.

* ![Captura de pantalla 2025-04-01 212822](https://github.com/user-attachments/assets/a7cf45a5-3762-446a-b858-01cbdb13f900)

creando la credencial: 

![Captura de pantalla 2025-04-01 230423](https://github.com/user-attachments/assets/5103aa57-3906-4188-92c3-2ef18119478a)

![Captura de pantalla 2025-04-01 230441](https://github.com/user-attachments/assets/73701802-4029-4c35-a2b6-c387847e7153)

creación del agente: 


![Captura de pantalla 2025-04-01 230904](https://github.com/user-attachments/assets/07f3eeaf-c18c-47ff-ac5a-0621cc12be03)

![Captura de pantalla 2025-04-02 104315](https://github.com/user-attachments/assets/67d4fdfc-a1eb-4e41-b478-c39f4ae2244f)


![Captura de pantalla 2025-04-02 104213](https://github.com/user-attachments/assets/96263af7-0a24-4b00-a1b2-6964a2158e5d)

confuguring the task: 
![Captura de pantalla 2025-04-02 105036](https://github.com/user-attachments/assets/91bb73a0-a629-4655-93d8-74d89a5b4f35)
![Captura de pantalla 2025-04-02 105050](https://github.com/user-attachments/assets/a4fd22f4-930b-41d1-bb43-4b79a57c7e77)


![Captura de pantalla 2025-04-02 104315](https://github.com/user-attachments/assets/6ac1e42a-3dae-4eb4-a736-f701357a1100)

![Captura de pantalla 2025-04-02 105107](https://github.com/user-attachments/assets/76113059-49be-40fe-a0c4-73d6a7944de3)


![Captura de pantalla 2025-04-02 104907](https://github.com/user-attachments/assets/63549330-1cf3-48a9-9837-c385ce88c4ba)


success!

#Run the nginx machine
Open a browser and go to http://<SERVER_IP>:8080.

![Captura de pantalla 2025-04-02 104853](https://github.com/user-attachments/assets/3227d568-36e3-41ec-8a86-f271e7caa547)





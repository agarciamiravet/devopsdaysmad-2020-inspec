## DevOps Madrid 2020 - Audita y evalua la seguridad de tu infraestructura con Inspec

Código mostrado durante la charla sobre Inspec dado el 21 de febrero de 2020 en DevOps Madrid

 1. **Azure - Profile de Inspec para auditar la plataform de Azure**

     En el repositorio [https://github.com/agarciamiravet/devopsdaysmad-inspec-azure-platform](https://github.com/agarciamiravet/devopsdaysmad-inspec-azure-platform) podeís encontrar el profile de Inspec que analiza la plataforma de Azure. En este profile únicamente se analizan tanto máquinas virtuales como Storage Accounts.
     Este repositorio contiene una  pipeline de Jenkins para automizar este proceso.
     
 2.  **Azure - Código de Terraform y Profile de Inspec que valida lo desplegado con Terraform.**
      
      En el repositorio [https://github.com/agarciamiravet/devopsdaysmad-inspec-azure](https://github.com/agarciamiravet/devopsdaysmad-inspec-azure) esta tanto el código de Terraform como el profile de Inspec que valida lo desplegado con Terraform.

	    Incluyo pipeline de Jenkins para ver como podría desplegarse tanto el código como el profile de Inspec.
         
3. **AWS - Profile de Inspec para auditar la plataforma AWS**
   
   En el repositorio [https://github.com/agarciamiravet/devopsdaysmad-inspec-aws-platform](https://github.com/agarciamiravet/devopsdaysmad-inspec-aws-platform) podeís encontrar el profile que valida la plataforma AWS, En este caso el profile hereda de otro profile ofrecido por el MITRE, cuya url es [https://github.com/mitre/cis-aws-foundations-baseline](https://github.com/mitre/cis-aws-foundations-baseline).
   Este profile traslada a tests de Inspec el CIS Benchmark de AWS que puedes obtener en la siguiente url:
https://d1.awsstatic.com/whitepapers/compliance/AWS_CIS_Foundations_Benchmark.pdf

4. **AWS - Código de Terraform , Playbooks de Ansible y Profile de Inspec que valida lo desplegado en Terraform.**
    
    En el repositorio [https://github.com/agarciamiravet/devopsdaysmad-inspec-aws](https://github.com/agarciamiravet/devopsdaysmad-inspec-aws) podeís encontrar el código de Terraform , los playbooks de Ansible y el profile de Inspec que valida tanto el código de terraform como luego los playbooks de Ansible.

	Incluyo pipeline de Jenkins para ver como podría desplegarse tanto el código como el profile de Inspec.
    
5. **GCP -  Profile de Inspec para auditar la plataforma Google Cloud Platform**

     En el repositorio [https://github.com/agarciamiravet/devopsdaysmad-inspec-gcp-platform](https://github.com/agarciamiravet/devopsdaysmad-inspec-gcp-platform) podeís encontrar el profile que valida la plataforma AWS, En este caso el profile hereda de otro profile ofrecido directamente por Google, cuya url es [https://github.com/GoogleCloudPlatform/inspec-gcp-cis-benchmark](https://github.com/GoogleCloudPlatform/inspec-gcp-cis-benchmark)

   Este profile traslada a tests de Inspec el CIS Benchmark de GCP que puedes obtener en la siguiente url:
[https://www.cisecurity.org/blog/new-cis-benchmark-for-google-cloud-computing-platform/](https://www.cisecurity.org/blog/new-cis-benchmark-for-google-cloud-computing-platform/)    

6. **GCP - Código de Terraform y Profile de Inspec que valida lo desplegado en Terraform.**
	
	En el repositorio [https://github.com/agarciamiravet/devopsdaysmad-inspec-gcp](https://github.com/agarciamiravet/devopsdaysmad-inspec-gcp) que valida lo desplegado con Terraform así como el Profile de Inspec que valida lo desplegado con  Terraform.

   Incluyo pipeline de Jenkins para ver como podría desplegarse tanto el código como el profile de Inspec.


Cualquier cosa que necesiteís  contactar a través de Twitter @alexmiravet o a través de correo eléctronico agarciamiravet@gmail.com

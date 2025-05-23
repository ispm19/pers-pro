AzureDevops, SonarQube, Docker, Kubernetes (EKS)
## Expected result

Requerimientos cumplidos

        1. Descarga y configuración inicial:
        
        2. Clonación del repositorio y setup de entorno.
        
        3. Instalación automática del framework (Node.js / Java / otro) en pipeline si no está presente.
        
        4. Análisis con SonarQube:
                Integración de SonarQube en el pipeline.
                ![image](https://github.com/user-attachments/assets/ab609acd-094e-469d-9ae5-b59a9fbcfde1)
                
                Se contemplan dos escenarios:

                        Análisis fallido: el pipeline se detiene.
        
                        Análisis exitoso: continúa con compilación.
        
        5. Compilación y generación de imagen Docker:
        
                Imagen Docker construida en pipeline.
        
                Push automático a DockerHub.
                ![image](https://github.com/user-attachments/assets/31e5cd21-c56a-49bf-a201-ede6bf7a5d7d)
                
        6. Ejecución de comandos paralelos:
        
                Job paralelo imprime "Hola Mundo" 10 veces.
        
                Script Bash/Powershell crea 10 archivos con la fecha actual y los imprime.
                ![image](https://github.com/user-attachments/assets/09d24ba7-f76b-4350-ba51-aaaf8ece9539)

        7. Despliegue a Kubernetes (EKS):
        
                Aplicación desplegada en clúster EKS.
        
        8. Archivos YAML organizados en carpeta /environment.

        9. Ingress expone endpoint externo.

Bonus incluidos

✅ Infraestructura como código: (Revisar Terraform dir)

Creación de clúster Kubernetes con Terraform.

✅ Despliegue con Helm o Kustomize

Uso de Helm para manejar despliegues reutilizables.

✅ Despliegue en nube pública (Revisar environment dir)
![image](https://github.com/user-attachments/assets/1b60d043-8e1c-4ff3-bd12-7680c9e7def3)


EKS (AWS) desplegado desde cero. 

✅ Exposición pública

Ingress configurado con hostname accesible vía Internet. (http://ac62abd3701c04dc2b0e0588467e040a-1482966145.us-east-1.elb.amazonaws.com/)

✅ Metodología DevOps aplicada

Integración con herramientas de calidad, automatización end-to-end.
(Azure-pipeline.yaml).





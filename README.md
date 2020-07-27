# Cluster de Kubernetes con Vagrant

## Instalación

1. Clonar este repositorio.
2. Arrancar el cluster:

    ```
    vagrant up
    ```

3. Si no está instalado, instalar `kubectl` en el host:

    ```
    brew install kubernetes-cli
    ```
    
4. Copiar el fichero `.kube/config` desde el nodo `master` al host.
5. Probar que conecta correctamente: 

    ```
    kubectl cluster-info
    ```

## Referencias

- [Kubernetes Setup Using Ansible and Vagrant](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)
- [Using Ansible to Create a Kubernetes Cluster on a Virtual Lab](https://graspingtech.com/create-kubernetes-cluster/)
- [Creación de un Clúster de Kubernetes usando Vagrant y Ansible en 3 minutos](https://www.itwonderlab.com/es/cluster-kubernetes-vagrant-ansible/)

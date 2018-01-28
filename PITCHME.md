# Duchesse

### D'un conteneur à la production

---

### Qui suis je ? 

---

### De quoi on va parler ? 

- Conteneur et docker <!-- .element: class="fragment" -->  
- Kubernetes <!-- .element: class="fragment" -->  
- OpenShift <!-- .element: class="fragment" --> 

---

## Conteneurs 

![Image-Absolute](assets/img/containers.png)  

---

### Un conteneur ce n'est pas 

<br> 
- Ce n'est pas une VM  <!-- .element: class="fragment" --> 
- Ce n'est pas que docker  <!-- .element: class="fragment" -->

---

### Qu'est ce qu'un conteneur ? 

- Isolation d'un processus  <!-- .element: class="fragment" -->
- Format de packaging  <!-- .element: class="fragment" -->
- Open conteneur Initiative  <!-- .element: class="fragment" -->


---

### Pourquoi c'est cool ? 

- Reproductibilité des environements  <!-- .element: class="fragment" --> 
- Optimisation des ressources  <!-- .element: class="fragment" -->
- Facilité (eventuelle) à scaler  <!-- .element: class="fragment" -->


---


## Un peu de demo


Note:
- Demo d'un conteneur simple en local
- Vu des images
- Docker PS, docker stat
- PS, top


---

### Il faudrait orchestrer...

- Orchestration / scheduling  
- Garantie de HA  
- Optimisation des resources


![Image-Absolute](assets/img/multi-server.png)  



---

### Il faudrait persister...

![Image-Absolute](assets/img/kubernetes-volume.png)  


---

### Il faudrait exposer...

- Communication entre les services
- Load balancing


![Image-Absolute](assets/img/network.jpg)  


---

### Il faudrait sécuriser...

![Image-Absolute](assets/img/jail.gif)  

Note: 
Pas une VM => 


---

## Kubernetes

![Image-Absolute](assets/img/kubernetes-logo.png)  

---

### Un schéma d'architecture

![Image-Absolute](assets/img/kubernetes-archi.png)  

---

### A quoi ça sert ? 

- Scheduling  <!-- .element: class="fragment" --> 
- Persistent Volume  <!-- .element: class="fragment" -->
- Security Context  <!-- .element: class="fragment" -->

---

## OpenShift 

<img src="assets/img/openshift-logo.png" width="400">

---

### Facilité d'installation


<img src="assets/img/ansible-openshift.png" width="400">

Note: 
Production ready, 3 masters, sécurité, on prem

---

### Console d'administration

<img src="assets/img/webconsole.png" width="600">

---

### Sécurité 

- Gestion de user 
- Security Context Constraint 
- Registry avec authorisations
- Multi tenant

---

### Build, CI CD 

- Source to image (S2I)
- Integration Jenkins

---

### Et encore un schéma d'architecture...

![Image-Absolute](assets/img/arch-diagram.png)  

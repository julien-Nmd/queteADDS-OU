# quete ADDS-OU
quete pour creer une Unite d'Organisation dans d'AD DS de Windows Server  


## Sur ton Active Directory que tu as installé et configuré dans la quête précédente avec pour domaine wilders.lan

### - Créer une Unité d'Organisation Wilders_students

Dans Windows Server 2022 :  
Server Manager => Tools => Active Directory Administrative Center => A gauche on selectionne Domain Local => A droite en bas dans domain local :  
=> New => Organisation Unit  
Une fenêtre wizard s'ouvre "Create Organisation Unit" . Dans cette febêtre, on renseigne le nom de la OU en Wilders_students. 
 <P ALIGN="center"><IMG src="Capture d’écran (2).png" width=600></P>  
Puis OK  

### - Créer un Groupe d'utilisateurs Students

  
Puis dans le server manager.
Tools => Active Directory Users and Computers
 <P ALIGN="center"><IMG src="Capture d’écran (3).png" width=600></P>  

Ensuite on va se mettre dans Wilders_Students.  
Dans la fenêtre de droite, clique droit, New Group.

<P ALIGN="center"><IMG src="Capture d’écran (4).png" width=600></P>  

Dans le wizard quui s'ouvre on met Students dans Name => OK
<P ALIGN="center"><IMG src="Capture d’écran (5).png" width=400></P>  

### - Créer un utilisateur au sein de ce groupe  

On clique sur Users, puis dans la fenêtre de droite, clique droit => New User

<P ALIGN="center"><IMG src="Capture d’écran (6).png" width=600></P>  

Là on renseigne le nom d'utilisateur, dans notre exemple, au hasard.. Toto !  

<P ALIGN="center"><IMG src="Capture d’écran (7).png" width=400>&nbsp &nbsp &nbsp<IMG src="Capture d’écran (8).png" width=400></P>    

Puis on va dans Wilders_Students => A droite on double clique sur Students => Onglet Members => Add => On écrit Toto  

<P ALIGN="center"><IMG src="Capture d’écran (9).png" width=600></P>    



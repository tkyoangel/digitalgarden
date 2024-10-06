---
{"dg-publish":true,"permalink":"/Cinématique/Accélération d'un point matériel/","tags":["gardenEntry"]}
---

## Vecteur accélération instantanée

On écrit le vecteur accélération instantanée :
$$\vec{a} = \frac{\mathrm{d}\vec{v}}{\mathrm{d}t} = \frac{\mathrm{d}^2\vec{OM}}{\mathrm{d}t^2}$$
*il représente le taux de variation du vecteur vitesse par unité de temps*


## Composantes dans différents repères

### Coordonnées cartésiennes

$$\vec{a} = \frac{\mathrm{d^2}x}{\mathrm{d}t^2} \vec{e_x} + \frac{\mathrm{d^2}y}{\mathrm{d}t^2} \vec{e_y} + \frac{\mathrm{d^2}z}{\mathrm{d}t^2} \vec{e_z}$$
### Coordonnées cylindriques
*voir [[Cinématique/Aide - Rappels OMNI/Dérivation des vecteurs unitaires (par rapport au temps)#Dérivée du vecteur e theta\|Dérivation des vecteurs unitaires (par rapport au temps)#Dérivée du vecteur e theta]]*

$$\vec{a} = (\overset{..}{r} - r \overset{.}{\theta^2})\vec{e_r} \ + \ (2\overset{.}{r}\overset{.}{\theta} \ + \ r \overset{..}{\theta})\vec{e_\theta} + \overset{..}{z}\vec{e_z}$$
(démonstration : [[Poly Meca.pdf#page=65]])

### Dans la base de Frenet

*pour rappel, on avait défini dans [[Cinématique/Vitesse d'un point matériel\|Vitesse d'un point matériel]] :*
$$\vec{v} = \frac{\mathrm{d}l}{\mathrm{d}t} \vec{u_T}$$
Ainsi, 

$$\vec{a} = \frac{\mathrm{d}\vec{v}}{\mathrm{d}t} = \frac{\mathrm{d^2}l}{\mathrm{d}t^2} \vec{u_T} + \frac{\mathrm{d}l}{\mathrm{d}t}\frac{\mathrm{d}\vec{u_T}}{\mathrm{d}t}$$

$$\text{On peut y réécrire sous la forme : } \frac{\mathrm{d^2}l}{\mathrm{d}t^2} \vec{u_T} + \frac{\mathrm{d}l}{\mathrm{d}t} \frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l} \frac{\mathrm{d}l}{\mathrm{d}t} = \frac{\mathrm{d^2}l}{\mathrm{d}t^2}\vec{u_T} + (\frac{\mathrm{d}l}{\mathrm{d}t})^2 \frac{\mathrm{d}\vec{u_T}}{\mathrm{d}l}$$

*On identifie ensuite l'expression du vecteur uN, voir [[Cinématique/Base de Frenet\|Base de Frenet]]*

$$\vec{a} = \frac{\mathrm{d^2}l}{\mathrm{d}t^2} \vec{u_T} \ + \ (\frac{\mathrm{d}l}{\mathrm{d}t})^2 \frac{\vec{u_N}}{R_C}$$



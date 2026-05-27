# Nirvana - Diagnostic

"Al crearse un household, se crea un ID para esa cuenta. Se puede ingresar con 2 de las 7 verifications" 

" Speaker tiene 13 hexanumeric digits it is a mac address " 

## Rules for a diagnostic

* Most of the transmission remain for 20 mins before they are gone. "No reboot or Reset without a diagnostic" 
* Make a diagnostic before troubleshooting or making changes, and if you make changes look at  the diagnostic and note what we found important
* Get a diagnostic when audio plays 
* Si hacemos un diagnostic sin tener music playing podemos perder data
* Si tenemos un issues con el audio lo mejor siempre es play music and then do the diagnostic. 
  <Best practice, after fixing the issue we can make another dianostic to confirm that the issue has been solved>
* En los casos debemos pegar el link del diagnostico ya que estos duran meses y podemos ver los cambios que se han hecho. 


## Nirvana

* Only works with Sonos VPN it won't work at home.
* Household- Sonos system - They can be in the same location or in different. 
* To use an speker that belongs to another household the device most be removed
* Make sure that you are looking at the correct household 
* We cannot see the household name
* Music lover means that the customer has not added an personal information 
* No factory resets for beta's* 

## Diagnostic types

* Manual Diagnostic:
From Controller (App/ios/android), shows system and controller information

* Auto diagnostic:  
From Nirvana using *trigger diagnostic button*, shows system information 

* SNF (System not Found):
Only Controller information comes from the app (ios/android) Will tell us that it could not be found 
It will only show the sonos controler information

* Target Diagnostic:
It will show information about a spesific device. Helps for double nat. 

<They all three have priority 1, in cases of cannot connect because can't see the system, should try first SNF>


ZTE ZXHN F 689 > TP LINK DECO E4R ))) Sonos  \
                                              > Working 
All in one > Mesh node ))) sonos device      /

## Dialog

- Dmesg: It shows information about hardware (Puertos, y como se mueve la information) 

- AnaCapa: Software related > Data mananaged but must likely about how the data is handled in clouds > Apps and controlers

## Voice assistent

- Input device: Automatically hear and receive the command
- Playback speaker: Plays content requested   

# Audio Dropouts

- Collect Diag while is playing
  Anacapa Red letters
  WiFi TX PER more than 25-30
  AP TX Stats PER (Station MODE)
  AP RX B M PRR
  Per -Tx Q red numbers
  Direct Routing Matrix  (Only for group) 
  PHY erros todos en 0
  Noise Floor more than 5 jumps 

What is the data path between the router and that player?
Sonosnet or Station Mode?
If grouped?
Bad numbers
What is the enviorment?
What else is there?


  
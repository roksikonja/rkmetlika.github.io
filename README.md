Povezava do spletne strani: https://rkmetlika.github.io/

### Navodila za dodajanje objav

1. V mapi ```_posts``` ustvarimo novo datoteko.
    1. Poimenujemo jo: ```2020-03-10-obvestilo-dvorana.md``` (če objavimo novico 10. 3. 2020 z naslovom Obvestilo o 
    zaprtju dvorane). 
    
    
2. Nato kopiramo spodnje besedilo in ga prilepimo v prve vrstice nove datoteke. <naslov> zamenjamo z dejanskim naslovom, tj.
Obvestilo o zaprtju dvorane. Nujno je, da je naslov znotraj dvojnih navednic. Zadnja vrstica določa fotografijo, ki bo
prikazana na vrhu strani. Če nimamo posebne fotografije, potem te vrstice ne spreminjamo in bo prikazana osnovna fotografija.
Sicer pa naložimo najprej fotografijo v eno izmed map v mapi ```/assets/images/```, nato pa ```/assets/images/default.jpg```
zamenjamo s točno lokacijo fotografije (ne smemo pozabiti na končnico bodisi .jpg/.png).

        ---
        layout: post
        title: "<naslov>"
        background: '/assets/images/default.jpg'
        ---

3. Fotografijo vstavimo v samo besedilo tako, da v novo vrstico kopiramo:
    
        <img style="width: 100%" src="<lokacija>"/>

        // Primer: vstavljanje fotografije turnir-zenica-vsi.jpg v mapi /assets/images/2019-2020
        <img style="width: 100%" src="/assets/images/2019-2020/turnir-zenica-vsi.jpg"/>
        
4. Besedilo oblikujemo s posebnimi znaki.

    1. Naslovi.
            
            # Naslov 1
            ## Naslov 2
            ### Naslov 3
            
    2. Dekoracija teksta.
        
            ***krepko***
            **poševno**
            
    3. Povezave.
        
            [tukaj](www.google.com)
            
    4. Več navodil najdete [tukaj](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
    
### Navodila za dodajanje slik

1. V odpremo mapo ```assets``` in nato ```images```.

2. Presodimo, v katero mapo spada slika in jo odpremo.

3. V zgornjem desnem kotu izberemo ```Upload files```.

4. Naložimo slike preko pojavnega okna.

5. Sledi ***Navodilo za dodajanje objav***.
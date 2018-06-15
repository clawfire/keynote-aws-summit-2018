
![](/uploads/logo-dir-innov.png)

![](/uploads/aws.png)

<style>
section:first-of-type p+p img{
    width: 15%;
}
</style>

---

### SCÉNARIO reconnaissance de plat et conseil nutritionnel

Nous allons montrer les différents éléments nécessaires au fonctionnement optimal du mécanisme d’IA de type « machine learning » avec les briques Amazon suivantes :

- AWS IoT core
- AWS Lambda
- Amazon Sage Maker
- Amazon Alexa Voice Services

---

<iframe frameborder="0" src="https://s3.amazonaws.com/healthly-food-capture/index.html" style="background-color: white;"></iframe>


---

### Architecture

<img src="/uploads/aws-summit-diagram.png" class='no-limit'/>


---

### Parcours utilisateur cible

<img src="/uploads/user-experience.png" class='no-limit' />


---


<img class="image-aside no-limit" src="/uploads/lunch-tray-ml1.png" />
<span class="title-aside">Un projet de la Direction Innovation SMILE !</span>


---

### Approche

Découpage en zone d'intérêts<br/>
![](/uploads/lunch-tray-ml2.png)

Reconnaissance, grâce à un réseau de neurones, de chaque zone d’intérêt
![](/uploads/lunch-tray-ml3.png)


---

<div class="contacts">
    <div class="contact">
        <p class="alain">
        </p>
        <div>
            <h5 style="color:white">Alain Rouen</h5>
            <p>Directeur Technique<br />
                alain.rouen@smile.fr</p>
        </div>
    </div>
    <div class="contact">
        <p class="cedric"></p>
        <div>
            <h5 style="color:white">Cédric Ravalec</h5>
            <p>Responsable offre IoT<br />
                cedric.ravalec@smile.fr</p>
        </div>
    </div>
    <div class="contact">
        <p class="patrice"></p>
        <div>
            <h5 style="color:white">Patrice Ferlet</h5>
            <p>Ingénieur R&amp;D<br />
                patrice.ferlet@smile.fr</p>
        </div>
    </div>
</div>

---


<video src="/uploads/fin.m4v" autoPlay muted></video>



<style>

.slides .contacts {
    display: flex;
}

.slides .contacts .contact {
    flex: 1;
    display: flex;
    flex-direction: column;
    margin: .4em;
}


.slides .contact > p {
    height: 280px;
    background-size: cover;
    background-repeat: no-repeat;
    margin: 0;
}

.slides .contact > p.alain {
    background-image: url("/uploads/alain.png");
}

.slides .contact > p.cedric {
    background-image: url("/uploads/cedric.png");
}

.slides .contact > p.patrice {
    background-image: url("/uploads/patrice.png");
}

.slides .contacts .contact > div {
    background-color: #3B80FF;
    color: white;
    text-align: center;
}
.slides .contacts .contact > div p{
    font-size: 0.5em;
}

.controls {
    display: none !important;
}

.slide-background.present:first-child::after{
    content: "Deep Learning";
    width: 100%;
    background: white;
    left: 0;
    bottom: 0;
    color: $mainColor !important;
    line-height: 5em;
    font-size: 0.6em;
    padding: 0 2em;
}

.slide-background.present::after {
    background-image: url(/uploads/smile-s.png);
    content: " ";
    width: 15%;
    height: 15%;
    position: absolute;
    bottom: 54px;
    left: 22px;
    background-size: contain;
    background-repeat: no-repeat;
}

.slides .title-aside {
    float: left;
    font-size: .6em !important;
    width: 15%
}

.slides .image-aside {
    float: right;
    width: 80%
}

.footer { display: none }
.container { overflow-y: hidden!important}

</style>

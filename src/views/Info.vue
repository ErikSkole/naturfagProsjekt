<template>
    <div class="info">
        <div class="damn" id="topOne">
            <div class="contentDamn">
                <h1>Hva er rusmidler?</h1>
                <p> Rusmidler er en kategori av kjemiske stoffer som påvirker nervesystemet vårt og sanseapparatene våre. De er også avhengighetsskapende I varierende grader ut i fra stoffet
                    En underkategori av rusmidler er Narkotiske stoffer det rusmidlet vi har om tilhører denne underkategorien.
                    Det som er spesielt med narkotiske stoffer er at de virker bedøvende, sløvende og smertestilene og i kort sikt kan noen av dem virke oppkvikkende men hvert år dør rundt 300 personer i Norge i forbindelse med bruk av narkotiske stoffer 
                    I tillegg er de fleste narkotiske stoffer ulovlige og derfor kalles de ulovlige midlene narkotika eller illegale rusmidler (dette gjelder også for rusmidler som ikke er narkotiske stoffer men som er fortsatt ulovlige).
                </p>
            </div>
            <div class="imageDamn"></div>
        </div>
        <div class="damn">
            <div class="imageDamn2"></div>
            <div class="contentDamn">
                <h1>Rusmisbruk blant unge</h1>
                <p>Rusmidler som kokain blir mer og mer populære å bruke blant ungdom. Det er mange grunner til denne utviklingen. 
                    På den ene siden har kokainbruk spesielt på fest blitt en kultur blant unge. 
                    På den andre siden er det blitt ekstremt lett å få tak i rusmidler som kokain, da tjenester som Snapchat gjør det lett for selger og kjøper å få kontakt. 
                    I tillegg til dette er Snapchat spesielt dårlig til å regulere chatter, da de ikke har mulighet til dette.
                </p>
            </div>
        </div>
        <div class="damn">
            <div class="contentDamn">
                <h2>Hvorfor er det farlig?</h2>
                <p> Kokain er et ulovlig rusmiddel. Det er sterkt vanedannende og skadelig for hjertet og hjernen, ifølge Norsk Helseinformatikk.
                    Kokain fører til dødsfall over hele verden, ifølge SML.
                    Kokain ved engangsbruk kan føre til større risikotakning, som kan føre til ulykker. 
                    Ved vedvarende bruk kan man skade sentralnervesystemet sitt og kan føre til død. 
                </p>
            </div>
            <div class="imageDamn3"></div>
        </div>
        <div class="damn">
            <div class="imageDamn4"></div>
            <div class="contentDamn">
                <h2>Samfunnsproblemer</h2>
                <p> Kokain er blitt like vanlig som øl på fest for oss.
                    Både guttene og jentene fyller jevnlig på med striper. Det er da er lørdagen i gang for mange i russetiden.
                    Kokain har eksplodert for unge mellom 16-24 år.
                    Gjennomsnittlig så er det 265 som dør av rus hvert år i Norge. Det er 1/4 Amalie Skram skole!
                </p>
            </div>
        </div>
        <div class="damn3">
            <h2>Hvordan forebygge rusmisbruk</h2>
            <div class="avsnitt">
                <div class="avsn">
                    <h3>Ta klare standpunkt!</h3>
                    <p class="paragraf">Det er viktig at man vet hva man gjør og at man setter grenser tidlig, før det blir et problem. Helst også før man prøver i det hele tatt.</p> 
                </div>
                <div class="avsn">
                    <h3>Skap et godt vennemiljø:</h3>
                    <p class="paragraf">En annen veldig viktig ting er at man ikke skal måtte bli presset til å ta rusmidler. Man burde derfor bygge opp den riktige vennesirkelen med folk som man vet ikke skaper disse problemene. </p>
                </div>
                <div class="avsn">
                    <h3>Gjør deg litt selvopptatt:</h3>
                    <p class="paragraf">Det er viktig at man tenker på seg selv og sitt eget velvære og ikke for mye på andre. Man har lyst til å vite hva som er viktig for en selv og behovene som kommer med det. 
                        Det viktige er at man ikke skal bli presset til å gjøre noe man ikke vil. </p>
                </div>
                <div class="avsn">
                    <h3>Snakk om det:</h3>
                    <p class="paragraf">Om man har problemer med rus eller med tanker om at det er nødvendig å ta rusmidler, så er det viktig at man får snakket med noen. 
                        Enten om det er foreldre, helsesykepleier eller en venn du kan stole på så er det viktig for at man ikke skal sitte seg fast et sted. </p>
                </div>
                <div class="avsn">
                    <h3>Ikke Skyld på andre!</h3>
                    <p class="paragraf">Uansett om man har bygget opp en dårlig vennesirkel, om man har blitt presset til å gjøre det eller om man bare tenkte "Fuck it", så skal man aldri skylde på noen andre. 
                        Det var altid et valg som DU SELV kunne tatt. Så med mindre noen bokstavelig talt holdt deg nede og trøkket kokain i trynet på deg, så kunne du ha gjort noe med det.</p>
                </div>
            </div>
        </div>
        <div class="avsn2">
            <router-link to="/kontakt" class="message">Husk! Det er aldri for sent å snu!</router-link>
        </div>
    </div>
</template>

<style scoped> 
#topOne {
    margin-top: 4rem;
}

.damn {
    margin: 1rem;
    margin-bottom: 5rem;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.damn3 {
    margin: 1rem;
    margin-bottom: 5rem;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.contentDamn {
    max-width: 40%;
}

.høyre {
    display: flex;
    justify-content: flex-end;
}

p {
    font-size: 20px;
}

.avsnitt {
    margin: 1rem;
    display: flex;
    flex-direction: row;
}

.avsn {
    margin: 1rem;
}

.avsn2 {
    display: flex;
    justify-content: center;
}

.message {
    display: flex;
    padding: 1.5rem;
    border-radius: 25px;
    color: white;
    background-color: rgb(59, 105, 255);
    text-decoration: none;
    font-size: 25px;
}

a.router-link-exact-active {
    background-color: rgb(59, 105, 255);
    color: white;
}

a:hover {
    transition: ease-in 0.5s;
    background-color: #ABBA;
}

.imageDamn {
    max-width: 40rem;
    max-height: 40rem;
    min-width: 40rem;
    min-height: 40rem;
    background-image: url('../assets/alexander-grey-FEPfs43yiPE-unsplash.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}

.imageDamn2 {
    max-width: 40rem;
    max-height: 40rem;
    min-width: 40rem;
    min-height: 40rem;
    background-image: url('../assets/colin-davis-pJgSrU_e2Ks-unsplash.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}

.imageDamn3 {
    max-width: 40rem;
    max-height: 40rem;
    min-width: 40rem;
    min-height: 40rem;
    background-image: url('../assets/gras-grun-6ScKApDyAMQ-unsplash.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}

.imageDamn4 {
    max-width: 40rem;
    max-height: 40rem;
    min-width: 40rem;
    min-height: 40rem;
    background-image: url('../assets/gras-grun-iCHacuW8BcI-unsplash.jpg');
    background-size: cover;
    background-repeat: no-repeat;
}
</style>
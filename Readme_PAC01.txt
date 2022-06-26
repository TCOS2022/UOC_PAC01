20220626

Tenim diferents cosetes aqui, a les branques dev_float i dev_flex hi em desenvolupat les diferents maneres de posicionament. Al final ho he importat tot aqui. 

Aqui tenim 3 jocs de pagines:

index-figma.html intenta ser el mes semblant a la pagina proposada a figma, tot i qeu he tingut que recorrer a ajustos manuals

index_fluid.html es una versio simplificada de la anterior on he intentat que tot fos amb mides percentuals i relatives. He afegit tambe 4 punts de canvi tipus mediaquerie
tot i que no se exctaament quin aspecte esperaveu que tingues, he jugat una mica amb el flex posant ho vertical i horitzontal i canviant el tamany de la font

Tambe he fet camvis, els mes apreciables son a la barra de menu i al footer
    Barra de menu -> apilada o be sense separacio entre element en les vistes mes petites
    footer: canvia la separcio dels elements en la vista mes petita

He intenat replicar la mateixa estructura en les tres pagines, de manera que despres pogues aplicar les mateixes clases pero m he trobat que al ser seccions amb elements molt
diferents, era mes facil atacarles per separat que no intentar de homogeneitzar-les. Aixi qeu de fet, la estructura basica seria:

    HEADER 
        NAV

    MAIN
        SECTION - TITLE
        SECTION .1
        ....

    FOOTER

I tambe cada section es divideix en un titol h2 i un contenidor, normalment de la clase "flex-container" si te items que es puguin ordenar 

    SECTION 
        h2 

        div/ul/table/..... 

He fet servir clases i selectors en cascada indiferentment, suposo que es podria reduir tot a clases, i segurament els selctors tambe es podrien simplificar, pero a mi m ha sigut
mes facil escriure la "cadena" (per exemple: section div ul li a img) pq aixi tinc mes present on estic. Entenc que amb mes practica, aixo no caldra.

Tambe he intentat seguir les recomancions, per exemple la de posar la navegacio sempre com una llista, tot i qeu tambe he probat a fer-ho sense, ambos casuistiques estan omplementades en el codi 
per exemple en el nav de la pagina del cv i en el footer. 

Per la icona de la caseta, i de les xarxes socials he fet servir els exportats desde figma. Les grafiques de html/css/js les he fet amb el inkscape i he inclos el titol a dintre.

Com al final he fet servir imatges aleatories al titol, li he afegit una mica de entorn verd pq segons la iamtge, simplement no es veia res.

Tambe he afegit una mica de shadow als H2.




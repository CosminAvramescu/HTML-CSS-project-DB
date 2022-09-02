Cele 3 animatii CSS sunt la butoanele de FROM / NIGHT (rotatie, border rosu si translatareY)
si la paginarea de jos stanga (butonul de inapoi se translateazaX si se scaleaza, iar 
butonul de next am transformarea matrix si scalare). La butonul de next animatia seamana
cu o pagina de carte care se ridica pentru a trece la urmatoarea pagina.

Abordarea generala este urmatoarea: in body am pus carusel, containerul care contine cele
6 carduri cu cazari intr-un card mai mare si randurile din sectiunea de footer. Schimbarea
pozelor de la cazare la hover am facut-o cu javascript in-place cand am declarat fiecare
imagine. La carusel n-am pus link la poze (am pus folder cu poze) deoarece am vrut sa 
descarc doar poze care au aceeasi dimensiune pentru carusel (1920*1080). Am incercat sa ma
folosesc cat mai mult de Bootstrap si de clasele deja implementate care vin odata cu acesta.

Am pus un icon 'X' langa selectoarele de destinatii, iar acesta sterge selectia cand este
apasat.
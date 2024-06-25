Basta adicionares no teu site Index.html um <div></div> com a seguinte informação:

    <div id="person"> </div>

E caso não tenhas no inicio no <head>

    <link rel="stylesheet" href="styles.css"> ou o href="(css que usas)"

E no styles.css ou o css que usas

#person {
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background-color: gray;
    position: relative;
    margin: 20px;
}
#person::after {
    content: "";
    position: absolute;
    height: 20px;
    width: 40px;
    background-color: gray;
    top: 22px;
    left: -10px;
    border-radius: 50% 50% 0% 0%;
}

Feito por Custodio
Creditos: (INSTA) _dailycoding

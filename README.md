# Css
Diseño de contador
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    font-family: Montserrat, sans-serif;
    background: #1666c2;
}

.contenedor{
    display: flex;
    width: 300px;
    height: 320px;
    color: white;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    border-radius: 20px;
    background: #33a5e7;
    box-shadow:  7px 7px 7px #248bdf,
             -7px -7px 7px #3b80e7;
}

.contar{
    font-size: 5rem;
}

.botones{
    margin-top: 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

button{
    margin: 5px;
    width: 70px;
    height: 25px;
    cursor: pointer;
    font-size: 1.5rem;
    background: white;
    border:none;
    border-radius: 5px;
}

span{
    color:#4c79da;
}

.reset{
    width: 50px;
    height: 25px;
}

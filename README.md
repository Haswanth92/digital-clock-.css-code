# digital-clock-.css-code
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

header {
    position: relative;
}

header {
    position: relative;
}

header img {
    z-index: 1;
    width: 100%;
}


.main {
    /* Positions over the Image completely centered */
    z-index: 2;
    text-align: center;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    /* Additional Settings */
    color: black;
    background: #ccc;
    height: 200px;
    border: 25px solid gray;
    padding: 0px 7px 28px 7px;
    border-radius: 15px;
    width: 455px;
}

.badge {
    position: relative;
    top: -40px;
    display: inline-block;
    color: white;
    padding: 5px;
    background: red;
    font-weight: bold;
    border-radius: 7px;
}

.clock {
    font-family: 'Orbitron', sans-serif;
    color: darkgreen;
}

span {
    font-size: 4.25rem;
}


@media (max-width: 900px) {
    .main {
        height: 175px;
        border: 25px solid gray;
        padding: 0px 7px;
        border-radius: 15px;
        width: 405px;
    }

    span {
        font-size: 3.25rem;
    }


}

@media (max-width: 740px) {
    .main {
        height: 150px;
        width: 295px;
    }

    span {
        font-size: 2.25rem;
    }
}

@media (max-width: 555px) {
    .main {
        height: 135px;
        width: 250px;
    }

    span {
        font-size: 1.5rem;
    }
}

@media (max-width: 425px) {
    .main {
        height: 125px;
        width: 210px;
    }

    span {
        font-size: 1rem;
    }
}

@media (max-width: 320px) {
    .main {
        width: 180px;
    }

    span {
        font-size: 0.8rem;
    }
}

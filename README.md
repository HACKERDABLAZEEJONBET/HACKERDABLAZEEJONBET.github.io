.context-options .context-option {
    width: 165px;
    height: 43px;
    border: 2px solid rgb(255, 0, 0);
    color: rgb(255, 0, 0);
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
    background: rgba(0, 0, 0, 0.8);
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    border-radius: 26px;
    z-index: 3;
    box-shadow: rgba(255, 0, 0, 0.5) 0px 0px 10px;
    transition: background-color 0.3s, transform 0.2s, box-shadow 0.2s;
    transform: scale(1);
}

/* Efeito ao clicar */
.context-options .context-option:active {
    transform: scale(0.95);
    box-shadow: 0 0 20px red, 0 0 40px rgba(255, 0, 0, 0.6);
    background-color: rgba(255, 0, 0, 0.2);
}

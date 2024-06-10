<div class="main">
        <div class="control">
            <div class="colorMenu">
                <div class="whitePlain"></div>
                <div class="greyPlain"></div>
                <div class="white"></div>
                <div class="yellow"></div>
                <div class="red"></div>
            </div>
            <div class="keyShape">
                <div class="circButton"></div>
                <div class="sqButton"></div>
            </div>
            <div class="keyPrint">
                <div>A</div>
            </div>
            <div class="reset">
                <svg viewBox="0 0 102.52 122.88" >
                    <g>
                        <path
                        d="M56.9,9.2l-8.75,44.47L39.28,40.3C20.17,47.97,9.44,60.62,7.85,80.09c-15.7-27.44-6.16-52.04,13.73-66.45 L12.52,0L56.9,9.2L56.9,9.2L56.9,9.2L56.9,9.2L56.9,9.2z M45.61,113.68l8.75-44.47l8.87,13.37c19.11-7.67,29.83-20.32,31.43-39.79 c15.7,27.44,6.16,52.04-13.73,66.45l9.05,13.64L45.61,113.68L45.61,113.68L45.61,113.68L45.61,113.68L45.61,113.68z" />
                    </g>
                </svg>
            </div>
            <div class="theme"></div>
        </div>
        <!-- made specifically to house the 'before'-pseudo element -->
        <!-- since textArea doesn't support 'before'/'after' -->
        <div class="textContainer">
            <textarea placeholder=". . ." rows=1 class="text" spellcheck="false" autofocus></textarea>
        </div>

        <div class="keyboard">
            <div class="row">
                <div class="key" id="Escape">Esc</div>
                <div class="key" id="Digit1">1</div>
                <div class="key" id="Digit2">2</div>
                <div class="key" id="Digit3">3</div>
                <div class="key" id="Digit4">4</div>
                <div class="key" id="Digit5">5</div>
                <div class="key" id="Digit6">6</div>
                <div class="key" id="Digit7">7</div>
                <div class="key" id="Digit8">8</div>
                <div class="key" id="Digit9">9</div>
                <div class="key" id="Digit0">0</div>
                <div class="key" id="Minus">- _</div>
                <div class="key" id="Equal">= +</div>
                <div class="key" id="Backspace">Backspace</div>
                <div class="key" id="Insert">Ins</div>
                <div class="key" id="Home">Home</div>
            </div>
            <div class="row">
                <div class="key" id="Tab">Tab</div>
                <div class="key" id="KeyQ">Q</div>
                <div class="key" id="KeyW">W</div>
                <div class="key" id="KeyE">E</div>
                <div class="key" id="KeyR">R</div>
                <div class="key" id="KeyT">T</div>
                <div class="key" id="KeyY">Y</div>
                <div class="key" id="KeyU">U</div>
                <div class="key" id="KeyI">I</div>
                <div class="key" id="KeyO">O</div>
                <div class="key" id="KeyP">P</div>
                <div class="key" id="BracketLeft">[</div>
                <div class="key" id="BracketRightKey">]</div>
                <div class="key" id="Backslash">\ |</div>
                <div class="key" id="Delete">Del</div>
                <div class="key" id="End">End</div>
            </div>
            <div class="row">
                <div class="key" id="CapsLock">CapsLk</div>
                <div class="key" id="KeyA">A</div>
                <div class="key" id="KeyS">S</div>
                <div class="key" id="KeyD">D</div>
                <div class="key" id="KeyF">F</div>
                <div class="key" id="KeyG">G</div>
                <div class="key" id="KeyH">H</div>
                <div class="key" id="KeyJ">J</div>
                <div class="key" id="KeyK">K</div>
                <div class="key" id="KeyL">L</div>
                <div class="key" id="Semicolon">; :</div>
                <div class="key" id="Quote">' "</div>
                <div class="key" id="Enter">Enter</div>
                <div class="key" id="PageUp">PgUP</div>
                <div class="key" id="PageDown">PgDN</div>
            </div>

            <div class="row">
                <div class="key" id="ShiftLeft">Shift</div>
                <div class="key" id="KeyZ">Z</div>
                <div class="key" id="KeyX">X</div>
                <div class="key" id="KeyC">C</div>
                <div class="key" id="KeyV">V</div>
                <div class="key" id="KeyB">B</div>
                <div class="key" id="KeyN">N</div>
                <div class="key" id="KeyM">M</div>
                <div class="key" id="Comma">,</div>
                <div class="key" id="Period">.</div>
                <div class="key" id="Slash">/ ?</div>
                <div class="key" id="ShiftRight">RShift</div>
                <div class="key" id="ArrowUp">^</div>
            </div>
            <div class="row">
                <div class="key" id="ControlLeft">Ctrl</div>
                <div class="key" id="MetaLeft">Win</div>
                <div class="key" id="AltLeft">Alt</div>
                <div class="key" id="Space"> ---- </div>
                <div class="key" id="AltRight">Alt</div>
                <div class="key" id="fn">Fn</div>
                <div class="key" id="ControlRight">Ctrl</div>
                <div class="key" id="ArrowLeft">&lt;</div>
                <div class="key" id="ArrowDown">v</div>
                <div class="key" id="ArrowRight">&gt;</div>
            </div>
        </div>
        <div class="stats">
            <p class="wordCount">0</p>
            <span>words</span>
            <p class="wordSpeed">0</p>
            <span>wpm</span>
        </div>
    </div>
    
    <style>
@import url('https://fonts.googleapis.com/css2?family=Lexend+Deca&display=swap');

@keyframes spin {
    0%{
        transform: rotate(0deg);
    }
    100%{
        transform: rotate(360deg);
    }
}

:root {
    --theme: white;
    --antiTheme: rgb(40, 40, 40);
}

body {
    display: flex;
    justify-content: center;
    gap: 50px;

    margin: 0;
    height: 100vh;
    background-color: var(--theme);
}

/*  container of all: 
    1. controls-menu
    2. textArea
    3. keyboard
    4. stats
*/
.main {
    display: flex;
    flex-flow: column;
    justify-content: end;
    align-items: left;

    position: relative;

    font-family: 'Lexend Deca', sans-serif;
    font-weight: 700;
}

/* --------------------------------------------------------------------------- */
/* \\\\\\\\\\\\ */
/* CONTROL MENU */
.control {
    -webkit-user-select: none;
    user-select: none;

    display: flex;
    flex-flow: column;
    gap: 30px;

    position: absolute;
    bottom: 30%;
    left: -25%;
    margin-bottom: 25px;

    transition: all ease-in-out 0.2s;
    z-index: 2;
}

.control>div {
    display: flex;
    flex-flow: column;
    align-items: center;

    border: 2px solid rgb(191, 191, 191);
    border-radius: 20px;

    opacity: 45%;
    transition: all ease-in-out 0.5s;
}

.control>div:hover {
    opacity: 100%;
}

/* \\\\\\\\\\ */
/* COLOR MENU */
.colorMenu {
    padding: 18px 9px;
    gap: 15px;
}

.colorMenu>div {
    display: inline-block;
    border-radius: 50%;
    height: 12px;
    width: 12px;

    cursor: pointer;
    box-shadow: 0px 0px 9px 0.5px black;
}

/* COLOR MENU OPTIONS */
.whitePlain{
    background: white;
}
.greyPlain{
    background: black;
}
.white {
    background: linear-gradient(45deg, white 50%, black 50% 100%);
}
.yellow {
    background: linear-gradient(45deg, yellow 50%, black 50% 100%);
}
.selectedColor {
    animation: spin ease infinite 2s;
}
.red {
    background: linear-gradient(45deg, red 50%, black 50% 100%);
}

/* \\\\\\\\\\\\\ */
/* KEYSHAPE MENU */
.keyShape {
    padding: 16px 9px;
    gap: 12px;
}

.keyShape div {
    cursor: pointer;
    border: 2px solid rgb(40, 40, 40);
    background-color: white;
    box-shadow: 0px 3px 9px -2px rgb(40, 40, 40);
}

/* KEYSHAPE MENU OPTIONS */
.sqButton {
    background-color: var(--theme);
    transition: all ease-in 0.2s;
    height: 9px;
    width: 9px;
}

.sqButton:hover {
    background-color: var(--antiTheme);
}

.circButton {
    height: 12px;
    width: 12px;
    border-radius: 50%;
    background-color: var(--theme);
    transition: all ease-in 0.1s;
}

.circButton:hover {
    background-color: var(--antiTheme);
}

/* \\\\\\\\\\\\\\ */
/* KEY PRINT MENU */
.keyPrint {
    gap: 5px;
    padding: 14px 9px;
    color: var(--antiTheme);
    text-decoration: line-through;
    cursor: pointer;
}

.keyPrint>div {
    display: flex;
    justify-content: center;
    align-items: center;

    height: 12px;
    width: 12px;
    padding: 1px;
    border-radius: 50%;

    font-size: 12px;
}

/* \\\\\\\\\\\\\\\\\\\\ */
/* THEME CONTROL BUTTON */
.theme {
    padding: 10px 9px;
    background-color: var(--antiTheme);
    cursor: pointer;
}

/* \\\\\\\\\\\\\\\\\\\\ */
/* RESET BUTTON */
.reset {
    padding: 10px 9px;
    fill: var(--antiTheme);
    background-color: var(--theme);
    cursor: pointer;
}

/* --------------------------------------------------------------------------- */

/* --------------------------------------------------------------------------- */
.textContainer {
    display: flex;
    justify-content: center;
    position: relative;
}

/* \\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\ */
/* blurring gradient over textArea */
.textContainer::before {
    content: "";
    display: block;
    position: absolute;
    bottom: 100px;

    width: 105%;
    height: 100%;
    max-height: 1200px;

    cursor: pointer;
    background: linear-gradient(var(--theme), var(--theme), transparent);
    transition: all ease-in 1s;
}

/* \\\\\\\\ */
/* textArea */
.text {
    flex-wrap: wrap;

    resize: none;
    width: 100%;
    border: none;
    outline: none;
    overflow: hidden;

    font-family: 'Lexend Deca', sans-serif;
    font-size: large;
    text-decoration: none;
    color: rgb(156, 156, 156);
    caret-color: rgb(187, 187, 187);

    background-color: transparent;
}

.text::selection {
    color: var(--theme);

    /* this shade works for both dark/light mode */
    background-color: rgb(156, 156, 156);
}

/* --------------------------------------------------------------------------- */

/* --------------------------------------------------------------------------- */
.keyboard {
    -webkit-user-select: none;
    user-select: none;

    position: relative;

    padding: 10px;
    margin: 5% 0 18% 0;
    border-radius: 5px;

    font-size: 10px;
    color: rgb(40, 40, 40);
    box-shadow: 0 0px 4px -2px black, 0 20px 80px -30px black;
    background-color: white;
    transition: all ease-in-out 0.3s;
    z-index: 1;
}

/* for toggling to extra Shadow
   for the dark theme */
.keyboardBlackShadow {
    box-shadow: 0 0px 6px -2px black, 0 30px 100px -20px black;
}

/* used by 'keyPrint-button' &
   'keyboard-color changing menu' */
.whiteKeyPrint {
    color: white;
}

.row {
    display: flex;
}

.key {
    display: flex;
    align-items: center;
    justify-content: center;

    margin: 2px;
    width: 35px;
    height: 35px;
    border-radius: 1px;
    border: black solid 1px;

    box-shadow: 0px 3px 8px -1px black;
    transition: all ease 0.1s;
}

.key.circ {
    width: 35px;
    height: 35px;
    border-radius: 15px;
    border: 1px solid transparent;
    box-shadow: 0px 2px 8px 0px rgb(0, 0, 0);
}

#CapsLock,
#Enter {
    width: 76px;
    /* 2px margin +2px margin + 1px border + 1px border */
}
#Backspace{
    width: 76px;
    /* 2px margin +2px margin + 1px border + 1px border */
}

#Space {
    width: 240px;
}
/* #Space.circ {
    width: 235px;
} */

#Tab {
    width: 56.5px;
    /* 1.5 keys + 4px margin */
}

#Backslash {
    width: 54.5px;
}

#ShiftLeft,
#ShiftRight {
    width: 96.5px;
}

#MetaLeft,
#AltLeft,
#ControlLeft,
#AltRight,
#ControlRight,
#fn {
    width: 48.66px;
}

.pressed {
    box-shadow: 0px 0px 0px 0px rgb(0, 0, 0);
}
.pressed.circ {
    box-shadow: 0px 0px 0px -40px rgb(0, 0, 0);
}

/* --------------------------------------------------------------------------- */

/* --------------------------------------------------------------------------- */
.stats {
    position: absolute;
    bottom: 27%;
    right: -25%;

    opacity: 25%;
    margin-bottom: 25px;
    color: var(--antiTheme);
    transition: all ease-in-out 0.2s;
    z-index: 3;
}
.stats *::selection {
    color: var(--theme);

    /* this shade works for both dark/light mode */
    background-color: rgba(156, 156, 156, 0.8);
}

.stats:hover {
    opacity: 90%;
}

.stats span {
    color: rgb(81, 81, 81);
}

.wordCount,
.wordSpeed {
    margin: 20px 0 -7px 0;
    font-size: 20px;
}

/* --------------------------------------------------------------------------- */

@media (max-height:800px) {
    .textContainer::before {
        max-height: 1000px;
        background: linear-gradient(var(--theme), var(--theme), var(--theme), transparent);
    }

    .keyboard {
        margin: 2.5% 0 10% 0;
    }

    .control {
        bottom: 20%;
        gap: 20px;
    }
    
    .stats {
        bottom: 30%;
    }
}

@media (max-height:500px) {
    .textContainer::before {
        max-height: 400px;
        background: linear-gradient(var(--theme), var(--theme), var(--theme), var(--theme), transparent);
    }
    
    .keyboard {
        margin: 1% 0 5% 0;
    }
    
    .control {
        bottom: 12%;
        gap: 10px;
    }

    .stats {
        bottom: 40%;
    }
}

@media (max-width:1400px) {
    .stats {
        right: -18%;
    }
    .control {
        left: -18%;
    }
}
@media (max-width:1100px) {
    .stats {
        right: -12%;
    }
    .control {
        left: -12%;
    }
}    
    </style>

// https://chromedino.com/

const cheat = (() => {
    //Set speed
    Runner.speed = 100;
    //Save original function 
    let originalFunction = Runner.prototype.gameOver;
    // Overwrite
    Runner.prototype.gameOver = () => { };
    return originalFunction;
});

let startCheat = cheat();
// Reset original gameOver()
let stopCheat = (original) => Runner.prototype.gameOver = original;

let boxes = document.querySelectorAll(".box");
let resetButton = document.querySelector("#resetButton");
let newGame = document.querySelector("#new-game");
let messagecontainer = document.querySelector(".msg-container");
let msg = document.querySelector("#msg");

let turno = true; // true = O's turn, false = X's turn

const winPatterns = [
    [0,1,2],
    [0,3,6],
    [0,4,8],
    [1,4,7],
    [2,5,8],
    [2,4,6],
    [3,4,5],
    [6,7,8]
];

// Add click event to each box
boxes.forEach((box) => {
    box.addEventListener("click", () => {
        if (box.innerText === "") { // Only allow click if box is empty
            if (turno) {
                box.innerText = "O";
            } else {
                box.innerText = "X";
            }
            turno = !turno; // Toggle turn
        } 
        box.disabled = true;
        checkWinner();
    });
});

// Optional: Reset button functionality
resetButton.addEventListener("click", () => {
    boxes.forEach((box) => {
        box.innerText = "";
    });
    turno = true; // Reset turn
});

const showWineer = (Winner) =>{
    msg.innerText = `Congratulations, Winner is ${Winner}`;
    messagecontainer.classList.remove("hide");

}
const disableBoxes= ()=>{
    for (let box of boxes) {
        box.disabled = true;
    }
}

const enableBoxes= ()=>{
    for (let box of boxes) {
        box.disabled = false;
        box.innerText = "";
    }
}

const resetGame= ()=>{
    turno = true;
    enableBoxes();
    messagecontainer.classList.add("hide");
}

const checkWinner = () =>{
    for (let pattern of winPatterns) {
       let pos1value = boxes[pattern[0]];
       let pos2value =  boxes[pattern[1]];
       let pos3value = boxes[pattern[2]];

       if(pos1value.innerText !== "" &&
    pos1value.innerText === pos2value.innerText &&
    pos2value.innerText === pos3value.innerText) {
    showWineer(pos1value.innerText);
    disableBoxes();
     }
    }
};

newGame.addEventListener("click", resetGame);
resetButton.addEventListener("click", resetGame);

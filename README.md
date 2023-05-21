# git_test

Hello Odin!

const calorieInput = document.querySelector("#calories");
const output = document.querySelector("#user-calories");

calorieInput.addEventListener("input", displayCalories);

function displayCalories () {
  output.innerHTML = calorieInput.value;
}

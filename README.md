setInterval(() => {
const allButtons = document.getElementsByClassName("x1lliihq x6ikm8r x10wlt62 x1n2onr6 xlyipyv xuxw1ft");
for (const button of allButtons) {
if (button.innerText === "Cancel request") {
button.click();
console.log('Canceled ✅');
return;
}
}
}, 500);

const menuBtn = document.querySelector('#open-menu-btn');
const CloseBtn = document.querySelector('#close-menu-btn');
const menu = document.querySelector('.nav__menu');

//OPEN MENU

menuBtn.addEventListener("click", () =>{
    menu.style.display = 'block';
    CloseBtn.style.display = 'inline-block';
    menuBtn.style.display = 'none';
});

//CLOSE MENU

const closeNav = () => {
    menu.style.display = 'none';
    CloseBtn.style.display = 'none';
    menuBtn.style.display = 'inline-block';
}

CloseBtn.addEventListener("click", closeNav);
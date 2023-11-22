document.addEventListener("DOMContentLoaded", function() {
    const menuIcon = document.querySelector('.menu-icon');
    const nav = document.querySelector('nav');
  
    // Agregar un evento de clic al ícono de hamburguesa para mostrar/ocultar la barra de navegación
    menuIcon.addEventListener('click', function() {
      nav.classList.toggle('open');
    });
  });
# Traduccion-Formulario
En el siguiente flujograma se puede ver el pseudocódigo  del ejercicio:
  
###Flujograma
1. Inicio
2. Modifico el titulo del formulario, trayendo el id del h2 y utilizando la propiedad de alteracion de contenido (innerText)   --- document.getElementById('form-signin-heading').innerText='Por favor inicia sesión'; 
3. Modifico los inputs de type ("email" y "password") (cajas donde colocar tus datos), trayendo el id de los input y utilizando la propiedad (placeholder) para realizar la modificacion --- document.getElementById('inputEmail').placeholder='Correo Electrónico';
document.getElementById('inputPassword').placeholder='Contraseña';
4. Modifico el input de type chekbox utilizando la propiedad de querySelector para obtener el selector, en este caso eltag span, traido del documento HTML, asimismo se utiliza innerText para la traduccion del texto --- document.querySelector('span').innerText='Recordar datos';
5. Se realiza el mismo proceso del punto 4, teniendo en cuenta que el selector que se trae del documento HTML es una clase del tag button docuemnt.querySelector('.btn').innerText='Iniciar Sesión';  
6. Fin

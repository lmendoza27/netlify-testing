<template>
  <div class="yo">
    
    <div class="contenido">

<h1 class="contact">Contact </h1>
      <form
  action="https://formspree.io/f/mvodyooa"
  method="POST"
>
    <input type="email" name="_replyto" class="correo"  placeholder="Email" required>
 <br><br>
    <textarea name="message" class="mensaje" placeholder="Message" required></textarea>
 <br><br>
  <!-- your other form fields go here -->
  <button type="submit" class="enviar">Send</button>
</form>
    </div>
<div class="llamada">
También puedes comunicarte conmigo al <b>+51 962 504 669</b> o escribirme:
<br>
<a href="https://api.whatsapp.com/send?phone=51962504669&text=Buen día Luis Ángel, te escribe ..." target="_blank">
<button class="whatsapp"> <i class="fab fa-whatsapp logo_wsp"></i> Escribir</button></a>
</div>
  </div>
</template>


<style lang="scss" src="../../src/assets/css/about.scss" scoped>
</style>

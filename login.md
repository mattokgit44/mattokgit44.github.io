---
theme: jekyll-theme-minimal
title: Login
permalink: /login/
---

<nav> 
  <ul> 
    <li><a href="/">Inicio</a></li>
    <li><a href="/login/">Login/Registro</a></li>
    <li><a href="/painel/">Painel</a></li>
  </ul>
</nav>

<style>
  nav ul {
    padding:0px;
  	margin:0px;
	  background-color:#EDEDED;
    display: flex;
    list-style: none;
  }
  nav ul li {
    margin-right: 10px;
  }
  nav ul li a {
    padding: 2px 10px;
	  display: inline-block;

	  /* visual do link */
	  background-color:#EDEDED;
	  color: #333;
	  text-decoration: none;
	  border-bottom:3px solid #EDEDED;
  }
  nav ul li a:hover {
    background-color:#D6D6D6;
	  color: #6D6D6D;
	  border-bottom:3px solid #EA0000;
    text-decoration: underline;
  }
</style>


# Login
<div id="modal-login" class="modal">
  <div class="modal-content">
    <form id="login-form">
      <div class="input-field">
        <input type="email" id="singup-email" required />
        <label for="singup-email">Endereço de email</label>
      </div>
      <div class="input-field">
        <input type="password" id="singup-password" required />
        <label for="singup-password">Senha</label>
      </div>
      <button class="btn yellow darken-2 z-depth-0">Entrar</button>
    </form>
  </div>
</div>

<a href="/registro" style="">Ainda não possui conta?</a>
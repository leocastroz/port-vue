<template>
  <div class="banner-1">

    <!-- NavBar -->

    <nav class="container px-6 mx-auto md:flex md:justify-between md:items-center" id="topinside" >
      <div class="flex items-center justify-between">
        <!-- LOGO SITE -->
        <div class="relative w-20 h-20">
          <img class="w-18 h-18" src="https://user-images.githubusercontent.com/72839343/184806880-49688d28-0fc0-4caf-9159-fb9cf863db6f.png" alt="LOGO SITE"/>
        </div>
        <!-- LOGO SITE -->



        <!-- Botão de menu -->

         <div @click="showMenu = !showMenu" class="flex md:hidden nav-icon">
          
            <input @click="showMenu = !showMenu" type="checkbox" id="checkbox-menu">
            <label for="checkbox-menu">
              <span></span>
              <span></span>
              <span></span>
            </label>
        </div>
      </div>

     

      <!-- Menu móvel aberto: "bloquear", Menu fechado: "oculto" -->

      <ul
        :class="showMenu ? 'flex' : 'hidden'"
        class="menu-box flex-col items-end mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0">
        <li class="menu-button"><a href="#maestrias" v-smooth-scroll></a></li>
        <li class="menu-button"><a href="#work" v-smooth-scroll>Trabalhos</a></li>
        <li class="menu-button"><a href="#testimonial" v-smooth-scroll>História</a></li>
        <li class="menu-button"><a href="#about" v-smooth-scroll>Visão de trabalho</a></li>
      </ul>
    </nav>

    <!-- Final Navbar -->

    <div class="flex items-center title-name">
      <div class="w-11/12 space-y-5 md:space-y-10">
        <h3 class="hello-button  w-fit md:py-3 md:px-5 py-1 px-2 rounded-lg 3xl:text-3xl 2xl:text-xl lg:text-xl md:text-md text-sm font-semibold">
          Doar um café &rarr; 
        </h3>
        <h4 class="3xl:text-8xl 2xl:text-7xl xl:text-5xl lg:text-4xl md:text-3xl sm:text-3xl text-xl">Sou Leonardo Castro
          <br />
          Desenvolvedor Front-end e Design Ui-Ux
        </h4>
      </div>
      

      <div class="w-10/12 flex justify-end">
        <img
          class="3xl:h-[800px] 2xl:h-[650px] xl:h-[550px] lg:h-[550px] md:h-[450px] sm:h-[350px]" src="https://user-images.githubusercontent.com/72839343/184799402-83e1a95d-35f9-4529-b962-debb50d00d26.png" alt="user image"/>
      </div>
    </div>
  </div>



  <div class="linguagens" id="maestrias">
    <svg width="52" height="12" viewBox="0 0 52 12" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M8.12399 3.87599L12 6.00277L8.12399 8.12402L5.99722 12L3.87598 8.12402L0 6.00277L3.87598 3.87599L5.99722 0L8.12399 3.87599Z" fill="#8257E6"></path>
      <path d="M28.124 3.87599L32 6.00277L28.124 8.12402L25.9972 12L23.876 8.12402L20 6.00277L23.876 3.87599L25.9972 0L28.124 3.87599Z" fill="#5AA2CB"></path>
      <path d="M48.124 3.87599L52 6.00277L48.124 8.12402L45.9972 12L43.876 8.12402L40 6.00277L43.876 3.87599L45.9972 0L48.124 3.87599Z" fill="#35E8B3"></path>
      </svg>
    <h1>Habilidades pessoais</h1>
    <div class="container-box">

      <div class="item-01">
        <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M14.1672 5V8C14.1257 8.50487 14.4965 8.94987 15.0006 9H21.6672C22.1713 8.94987 22.5422 8.50487 22.5006 8V5M13.332 35H11.6654C9.82442 35 8.33203 33.5076 8.33203 31.6667V8.33333C8.33203 6.49238 9.82442 5 11.6654 5H24.9987C26.8396 5 28.332 6.49238 28.332 8.33333V21.6667" stroke="url(#paint0_linear_8428_17866)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path d="M23.3333 34.9987L20 31.6654L23.3333 28.332" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path d="M28.332 28.332L31.6654 31.6654L28.332 34.9987" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <defs>
        <linearGradient id="paint0_linear_8428_17866" x1="6.97744" y1="10.8595" x2="34.4086" y2="25.4723" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        </defs>
        </svg>

        <p>100% de responsividade para smartphones</p>
      </div>

      <div class="item-01">
        <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M24.168 34.1667V33.49C24.1735 31.5648 25.7328 30.0055 27.658 30H33.178C35.1032 30.0055 36.6625 31.5648 36.668 33.49V34.1667C36.668 34.6269 36.2949 35 35.8346 35H25.0013C24.5411 35 24.168 34.6269 24.168 34.1667Z" stroke="url(#paint0_linear_8428_17889)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path fill-rule="evenodd" clip-rule="evenodd" d="M27.2089 23.3993C26.8049 21.9514 27.4199 20.4122 28.7105 19.6415C30.0011 18.8707 31.6479 19.0592 32.731 20.1016C33.8141 21.144 34.0655 22.7823 33.3448 24.1015C32.6241 25.4207 31.1096 26.0942 29.6472 25.7459C28.4683 25.4651 27.5347 24.5666 27.2089 23.3993Z" stroke="url(#paint1_linear_8428_17889)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path fill-rule="evenodd" clip-rule="evenodd" d="M3.33203 30.8346V30.158C3.33752 28.2328 4.89684 26.6735 6.82203 26.668H12.342C14.2672 26.6735 15.8265 28.2328 15.832 30.158V30.8346C15.832 31.2949 15.4589 31.668 14.9987 31.668H4.16536C3.70513 31.668 3.33203 31.2949 3.33203 30.8346Z" stroke="url(#paint2_linear_8428_17889)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path fill-rule="evenodd" clip-rule="evenodd" d="M6.37687 20.0672C5.97282 18.6193 6.58788 17.0801 7.87849 16.3094C9.16909 15.5387 10.8159 15.7272 11.899 16.7695C12.9821 17.8119 13.2335 19.4503 12.5128 20.7695C11.792 22.0886 10.2775 22.7622 8.81521 22.4139C7.63627 22.1331 6.70262 21.2346 6.37687 20.0672Z" stroke="url(#paint3_linear_8428_17889)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path d="M28.3333 10.0007C28.3333 13.6825 25.3486 16.6673 21.6667 16.6673C17.9848 16.6673 15 13.6825 15 10.0007C15 6.31875 17.9848 3.33398 21.6667 3.33398C25.3486 3.33398 28.3333 6.31875 28.3333 10.0007Z" stroke="url(#paint4_linear_8428_17889)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path d="M23.9091 8.67969L21.1091 11.478L19.4258 9.79969" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <defs>
        <linearGradient id="paint0_linear_8428_17889" x1="1.0742" y1="9.51884" x2="35.4479" y2="38.434" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        <linearGradient id="paint1_linear_8428_17889" x1="1.0742" y1="9.51884" x2="35.4479" y2="38.434" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        <linearGradient id="paint2_linear_8428_17889" x1="1.0742" y1="9.51884" x2="35.4479" y2="38.434" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        <linearGradient id="paint3_linear_8428_17889" x1="1.0742" y1="9.51884" x2="35.4479" y2="38.434" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        <linearGradient id="paint4_linear_8428_17889" x1="1.0742" y1="9.51884" x2="35.4479" y2="38.434" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        </defs>
        </svg>

        <p>Trabalho em equipe com metodologias ágeis</p>
        
      </div>

      <div class="item-01">

        <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M14.2942 27.3738C14.6847 27.7643 15.3179 27.7643 15.7084 27.3738C16.0989 26.9832 16.0989 26.3501 15.7084 25.9596L14.2942 27.3738ZM11.668 23.3333L10.9609 22.6262C10.7733 22.8138 10.668 23.0681 10.668 23.3333C10.668 23.5985 10.7733 23.8529 10.9609 24.0404L11.668 23.3333ZM15.7084 20.7071C16.0989 20.3166 16.0989 19.6834 15.7084 19.2929C15.3179 18.9024 14.6847 18.9024 14.2942 19.2929L15.7084 20.7071ZM25.7071 19.2929C25.3166 18.9024 24.6834 18.9024 24.2929 19.2929C23.9024 19.6834 23.9024 20.3166 24.2929 20.7071L25.7071 19.2929ZM28.3333 23.3333L29.0404 24.0404C29.431 23.6499 29.431 23.0168 29.0404 22.6262L28.3333 23.3333ZM24.2929 25.9596C23.9024 26.3501 23.9024 26.9832 24.2929 27.3738C24.6834 27.7643 25.3166 27.7643 25.7071 27.3738L24.2929 25.9596ZM7 6H33V4H7V6ZM34 7V33H36V7H34ZM33 34H7V36H33V34ZM6 33V7H4V33H6ZM7 34C6.44772 34 6 33.5523 6 33H4C4 34.6569 5.34315 36 7 36V34ZM34 33C34 33.5523 33.5523 34 33 34V36C34.6569 36 36 34.6569 36 33H34ZM33 6C33.5523 6 34 6.44772 34 7H36C36 5.34315 34.6569 4 33 4V6ZM7 4C5.34315 4 4 5.34315 4 7H6C6 6.44772 6.44772 6 7 6V4ZM35 10.6673H5V12.6673H35V10.6673ZM15.7084 25.9596L12.3751 22.6262L10.9609 24.0404L14.2942 27.3738L15.7084 25.9596ZM12.3751 24.0404L15.7084 20.7071L14.2942 19.2929L10.9609 22.6262L12.3751 24.0404ZM24.2929 20.7071L27.6262 24.0404L29.0404 22.6262L25.7071 19.2929L24.2929 20.7071ZM27.6262 22.6262L24.2929 25.9596L25.7071 27.3738L29.0404 24.0404L27.6262 22.6262Z" fill="url(#paint0_linear_8428_17882)"></path>
        <path d="M21.294 18.334L18.5156 28.334" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <defs>
        <linearGradient id="paint0_linear_8428_17882" x1="2.96811" y1="10.8595" x2="35.2069" y2="36.6203" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        </defs>
        </svg>
        
      <p>Desenvolvimento web e experiência Ui-Ux</p>

      </div>

      <div class="item-01">
        <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M10.21 23L5 28.3333L9.16667 30.8333L11.6667 35L18.165 28.175M21.8359 28.175L28.3343 35L30.8343 30.8333L35.0009 28.3333L29.7909 23M28.2483 8.41709C32.8044 12.9732 32.8044 20.3601 28.2483 24.9162C23.6922 29.4724 16.3052 29.4724 11.7491 24.9162C7.193 20.3601 7.193 12.9732 11.7491 8.41709C16.3052 3.86097 23.6922 3.86097 28.2483 8.41709Z" stroke="url(#paint0_linear_8428_17874)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <path fill-rule="evenodd" clip-rule="evenodd" d="M19.9993 20.9735L22.9943 22.5468C23.5777 22.8535 24.2593 22.3585 24.1477 21.7085L23.576 18.3735L25.9993 16.0135C26.471 15.5535 26.211 14.7518 25.5593 14.6568L22.211 14.1702L20.7143 11.1352C20.4227 10.5435 19.581 10.5435 19.2893 11.1352L17.7927 14.1702L14.4427 14.6585C13.791 14.7535 13.531 15.5552 14.0027 16.0152L16.426 18.3752L15.8543 21.7102C15.7427 22.3602 16.4243 22.8552 17.0077 22.5485L20.0027 20.9752H19.9993V20.9735Z" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        <defs>
        <linearGradient id="paint0_linear_8428_17874" x1="2.96805" y1="10.8595" x2="35.2071" y2="36.6213" gradientUnits="userSpaceOnUse">
        <stop stop-color="#05f7ff"></stop>
        <stop offset="1" stop-color="#3939fc"></stop>
        </linearGradient>
        </defs>
        </svg>
        

        <p>Entregas dentro do prazo para usuários</p>
      </div>
    </div>
  </div>






  <div class="banner-2 space-y-10 pb-20" id="work">
    <h3 class="heading5 my-5">Trabalhos Recentes</h3>
    <div class="card">
      <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
        <h4 class="project-title item">Clone Linktree</h4>
        <p class="font-work_sans pr-12">
          Neste projeto, foi desenvolvido um clone do "Linktree", plataforma
          onde usuários colocam suas redes sociais e compartilham uns com 
          os outros. Apesar de ser um projeto simples, não deixa 
          de ser clara a ideia de desenvolver algo semelhente ao original.
        </p>
        <br>
        <strong class="text-black font-medium">Acesse &rarr;</strong><a  href="https://clone-linktree-nu.vercel.app/" target="_blank" class="text-purple-500 font-medium">www.clonelinktree.com.br/ 👁‍🗨</a> 

        <button class="text-violet-600 font-bold text-1xl ">
          HTML 5 | CSS 3 | JS | VUE.JS | UI-UX
        </button> 
       

      </div>
      <div class="card-image bg-green-100">
        <img
          class="object-cover w-full h-72 md:h-96"
          src="https://img.olhardigital.com.br/wp-content/uploads/2021/05/Linktree-e1622124166688.png"
        />
      </div>
    </div>

    <div class="card">
      <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
        <h4 class="project-title item">CS - FireClub</h4>
        <p class="font-work_sans pr-12">
          Desenvolvi uma pequena loja funcional utilizando bastante "javascript",
          com funcionalidades semelhante a uma loja virtual para comprar algum 
          item. Também aproveitei e já desenvolvi a responsividade de todo site
          utilizando somente css puro.
        </p>
        <br>
        <strong class="text-black font-medium">Acesse &rarr;</strong><a  href="https://leocastroz.github.io/CS---FireClub/" target="_blank" class="text-purple-500 font-medium">www.csfireclub.com.br/ 👁‍🗨</a> 
         <button class="text-violet-600 font-bold text-1xl ">
          HTML 5 | CSS 3 | JS | UI-UX 
        </button> 
      </div>
      <div class="card-image">
        <img
          class="object-cover w-full h-48 md:h-96"
          src="https://i.ytimg.com/vi/3LFL2zO8zwI/sddefault.jpg"
        />
      </div>
    </div>


    <div class="card">
      <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
        <h4 class="project-title item">Vale Do Amazonas</h4>
        <p class="font-work_sans pr-12">
          Empresa destinada a público alvo para locação de veículos e transporte
          de passageiros há mais de 60 anos de mercado. Atualmente conta com frota 
          de 450 equipamentos, atendendo áreas de fretamento de ônibus, locação de
          veículos, locação de máquinas de terraplanagem, mineração e florestais.
        </p>
        <br>
        <strong class="text-black font-medium">Acesse &rarr;</strong><a  href="http://www.valedoamazonas.com.br/" target="_blank" class="text-purple-500 font-medium">www.valedoamazonas.com.br/ 👁‍🗨</a> 
         <button class="text-violet-600 font-bold text-1xl ">
          HTML 5 | CSS 3 | JS | JQUERY | UI-UX 
        </button> 
      </div>
      <div class="card-image">
        <img
          class="object-cover w-full h-48 md:h-96"
          src="https://technibus.com.br/wp-content/uploads/2021/04/vale-amazonas-Marcopolo.jpg"
        />
      </div>
    </div>

    <div class="card">
      <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
        <h4 class="project-title item">GTAV - FiveM</h4>
        <p class="font-work_sans pr-12">
          GTA V é um jogo desenvolvido pela Rockstar Games. Atualmente o jogo 
          tem dois modelos, sendo o Online e o Offline. Este projeto tem por finalidade
          adicionar scripts no jogo, adicionando roupas, acessorios, carros e etc....
          Logo, neste projeto foi desenvolvido um "smartwatch", capaz de pegar dados
          do jogador ao se logar no servidor, além de conter localização do jogo em tempo
          real e algumas notificações como: mensagem, música e status.    
        </p>
        <br>
        <strong class="text-black font-medium">Acesse &rarr;</strong><a  href="http://www.valedoamazonas.com.br/" target="_blank" class="text-purple-500 font-medium"> privado 🔒</a> 
         <button class="text-violet-600 font-bold text-1xl ">
          HTML 5 | CSS 3 | JS | JQUERY | API | JSON | NODE.JS | POO | BANCO DE DADOS | UI-UX 
        </button> 
      </div>
      <div class="card-image">
        <img
          class="object-cover w-full h-48 md:h-96"
          src="https://pbs.twimg.com/media/CJZxBNuUAAE1DxC.png"
        />
      </div>
    </div>

    <div class="card">
      <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
        <h4 class="project-title">Timblim</h4>
        <p class="font-work_sans pr-12">
          Plataforma de entreterimento, comunicação, diversão e etc...
          destinada ao público aberto, dentro da plataforma encontramos 
          um método parecido com facebook e instagram. Onde os usuários 
          se cadastram, ganham seguidores e podem explorar outros usuários.
        </p>
        <br>
        <strong class="text-black font-medium">Acesse &rarr;</strong><a  href="https://timblim.com/guest" target="_blank" class="text-purple-500 font-medium">www.timblim.com/ 👁‍🗨</a> 
       <button class="text-violet-600 font-bold text-1x1 ">
          HTML 5 | CSS 3 | JS | API | JQUERY | PHP | MYSQL | BOOTSTRAP | UI-UX | SCRUM |
        </button>
      </div>
      <div class="card-image">
        <img
          class="object-cover w-full h-48 md:h-96"
          src="https://user-images.githubusercontent.com/72839343/184925462-a15e69dc-de87-40ee-8c39-95452c84ddce.PNG"
        />
      </div>
    </div>
  </div>

  <div class="banner-2" id="testimonial">
    <div class="space-y-4 grid place-items-center mt-5">
      <svg width="52" height="12" viewBox="0 0 52 12" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M8.12399 3.87599L12 6.00277L8.12399 8.12402L5.99722 12L3.87598 8.12402L0 6.00277L3.87598 3.87599L5.99722 0L8.12399 3.87599Z" fill="#8257E6"></path>
      <path d="M28.124 3.87599L32 6.00277L28.124 8.12402L25.9972 12L23.876 8.12402L20 6.00277L23.876 3.87599L25.9972 0L28.124 3.87599Z" fill="#5AA2CB"></path>
      <path d="M48.124 3.87599L52 6.00277L48.124 8.12402L45.9972 12L43.876 8.12402L40 6.00277L43.876 3.87599L45.9972 0L48.124 3.87599Z" fill="#35E8B3"></path>
      </svg>
      <h3 class="heading3 text-purple-900">Escrevendo minha história</h3>
      <p class="font-work_sans text-white font-semibold leading-relaxed">
        Conteúdo postado diretamente por mim!
      </p>
    </div>

    <div class="max-w-6xl mx-auto px-8 py-16">
      <div class="relative">
        <div class="relative lg:flex rounded-lg shadow-2xl overflow-hidden">
          <div
            class="h-56 lg:h-auto lg:w-5/12 relative flex items-center justify-center negrafy"
          >
            <img
              class="absolute h-full w-full object-cover"
              src="https://user-images.githubusercontent.com/72839343/189807059-bfa2b7b0-18ed-4a6f-bc75-ce2e02953449.png"
              alt=""
            />
            <div class="absolute inset-0 bg-purple-700 opacity-10"></div>
            
          </div>
          <div class="relative lg:w-8/12 bg-me">
            
            <div
              class="relative py-12 lg:py-24 px-8 lg:px-16 text-blue-400 leading-relaxed"
            >
              <p>
                <strong class="text-white font-medium"> Desenvolvedor de software</strong>
                com 3 anos de experiência na função de freelancer. Trabalhando com  <strong class="text-white font-medium">HTML,CSS e JS.</strong>  2 anos e meio de experiência com <strong class="text-white font-medium">Vue.JS e Node.JS.</strong> Além disso, também trabalho com <strong class="text-white font-medium">Design UI | UX</strong> utilizando Figma, ademais gosto de contribuir em canais de voz como “Discord” tirando dúvidas de alguns devs. Também gosto de utilizar plataforma para versionamento de código: GIT, GitHub e Vercel. <br><br>

                <strong class="text-white font-medium" style="font-size:12px">MAESTRIAS &rarr;</strong><a href="/" class="text-blue-400 font-medium" style="font-size:12px"> HTML | CSS | JS | PHP | C++ | NODE.JS | VUE.JS | BOOTSTRAP | GIT | GITHUB | UI-UX | CLEAN CODE | PATTERN | KANBAN | SCRUM </a> 
              </p>
              <p class="mt-6">
                <a href="/">Autor</a>
                <a
                  href="https://www.linkedin.com/in/leoscastro/"
                  target="_blank"
                  class="font-medium text-yellow-600 hover:text-purple-400"
                >
                  &rarr; Leonardo Silva Castro 🥇</a
                >
              </p>
            </div>
          </div>
        </div>

        

        
        

        
      </div>
    </div>
  </div>


  

  <div class="banner-2 md:flex items-center md:justify-evenly" id="about">
  

    <img class="flutter" src="https://user-images.githubusercontent.com/72839343/185977454-ab183161-6f52-45d5-9011-591d13b24d16.png" alt="user image"/>
   
    <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-2/2">
      <h4 class="project-title-1 item">Minha visão de trabalho?</h4>
      <p class="font-work_sans text-white text-justify">
        Acredito que encontrar soluções para os problemas e o "x" da questão. 
        De fato, sempre precisamos ser eficientes naquilo que estamos fazendo,
        seja no trabalho ou em uma tarefa diária em casa.
        <br>
        <br />
        Exatamente por isso que você está aqui, buscando alguém que contribua
        positivamente e que atenda a demandas exigidas com prazos. Eu também não
        sei mentir, não sou nenhum mágico, não consigo construir nada grande com um curto 
        prazo. Também sou bastante sincero, gosto de falar quando não sei algo ou que 
        não darei conta de uma tarefa.
        <br>
        <br>
        Sempre gosto de passar minha visão, dar minha opinião sobre o que estamos 
        construindo e qual seria a melhor forma de encontrarmos a solução. 
      </p>
      <button class="focus-job  text-1xl ">
        Focus on work &rarr; #user
      </button>
    </div>
  </div>

  <div class="baixo">

    <div class="footer-type">
      <h2>Vamos trabalhar juntos e deixar tudo comentado e limpo!</h2>
      <a class="link-email">🏆castroz.dev@gmail.com</a>
    </div>

    <div class="footer">
      <div class="gap-2">
        <a href="https://github.com/leocastroz" target="_blank">   
        <img src="../src/assets/footer/github.svg" alt="facebook">
        </a>

        <a href="https://vercel.com/surinoto" target="_blank">
           <img src="../src/assets/footer/vercel.svg" alt="vercel">
        </a>

        <a href="https://www.facebook.com/LeonardoCastro.Leoneell/" target="_blank">
          <img src="../src/assets/footer/facebook.svg" alt="facebook">
        </a>

        <a href="https://www.linkedin.com/in/leoscastro/" target="_blank">      
          <img src="../src/assets/footer/linkedin.svg" alt="linkedin">
        </a>

        <a href="https://api.whatsapp.com/send?phone=+5594992195331&text=Olá! Leonardo Castro" target="_blank">       
          <img src="../src/assets/footer/whatsapp.svg" alt="whatsapp">
        </a>
      </div>
    </div>
    <div class="topo-site">
        <a href="#topinside" v-smooth-scroll><img src="../src/assets/footer/arrow.svg"></a>
      </div>
  </div>
</template>


<script>
  export default {
    data() {
      return {
        showMenu: false,
      }
    },
  }
</script>

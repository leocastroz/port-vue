<template>
  <div class="banner-1">

    <!-- NavBar -->

    <nav
      class="container px-6 mx-auto md:flex md:justify-between md:items-center"
    >
      <div class="flex items-center justify-between">
        <div class="relative w-20 h-20">
          <img
          class="w-18 h-18"
            src="https://user-images.githubusercontent.com/72839343/184806880-49688d28-0fc0-4caf-9159-fb9cf863db6f.png"
            alt="user image"
          />
        </div>

        <!-- Botão de menu -->

        <div @click="showMenu = !showMenu" class="flex md:hidden">
          <button
            type="button"
            class="text-purple-600 hover:text-purple-600 focus:outline-none focus:text-purple-600"
          >
            <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
              <path
                fill-rule="evenodd"
                d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
              ></path>
            </svg>
            
          </button>
        </div>
      </div>

      <!-- Menu móvel aberto: "bloquear", Menu fechado: "oculto" -->

      <ul
        :class="showMenu ? 'flex' : 'hidden'"
        class="flex-col items-end mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0"
      >
        <li class="menu-button"><a href="#">Home</a></li>
        <li class="menu-button"><a href="#work" v-smooth-scroll>Trabalhos</a></li>
        <li class="menu-button">
          <a href="#testimonial" v-smooth-scroll>História</a>
        </li>
        <li class="menu-button"><a href="#about" v-smooth-scroll>Extra📚</a></li>
      </ul>
    </nav>

    <!-- Final Navbar -->

    <div class="flex items-center">
      <div class="w-11/12 space-y-5 md:space-y-10">
        <h3
          class="hello-button text-black-700 w-fit md:py-3 md:px-5 py-1 px-2 rounded-lg 3xl:text-3xl 2xl:text-xl lg:text-xl md:text-md text-sm font-semibold font-work_sans"
        >
          ☕ Bem-vindo #user
        </h3>
        <h4
          class="3xl:text-8xl 2xl:text-7xl xl:text-5xl lg:text-4xl md:text-3xl sm:text-3xl text-xl font-medium leading-tight text-violet-500"
        >
          Sou
          <a
            href="https://www.linkedin.com/in/leoscastro/"
            target="_blank"
            class="text-green hover:underline text-blue-300"
          >
            Leonardo Castro</a
          ><br />Desenvolvedor Front-end e Design Ui-Ux
        </h4>
      </div>

      <div class="w-10/12 flex justify-end">
        <img
          class="3xl:h-[800px] 2xl:h-[650px] xl:h-[550px] lg:h-[550px] md:h-[450px] sm:h-[350px]" src="https://user-images.githubusercontent.com/72839343/184799402-83e1a95d-35f9-4529-b962-debb50d00d26.png" alt="user image"/>
      </div>
    </div>
  </div>

  <div class="banner-2 space-y-10 pb-20" id="work">
    <h3 class="heading3 my-5">Trabalhos Recentes</h3>
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
        <strong class="text-black font-medium">Acesse &rarr;</strong><a  href="https://clone-linktree-nu.vercel.app/" target="_blank" class="text-purple-500 font-medium"> clone-linktree-nu.vercel.app 👁‍🗨</a> 

        <button class="text-violet-600 font-bold text-1xl ">
          HTML 5 | CSS 3 | JS | VUE.JS | UI-UX
        </button> 
       

      </div>
      <div class="card-image bg-green-100">
        <img
          class="object-cover w-full h-72 md:h-96 rounded-lg"
          src="https://img.olhardigital.com.br/wp-content/uploads/2021/05/Linktree-e1622124166688.png"
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
          class="object-cover w-full h-48 md:h-96 rounded-lg"
          src="http://www.valedoamazonas.com.br/wp-content/uploads/2015/08/DSC00137-e1439250612569-1000x450.jpg"
        />
      </div>
    </div>

    <div class="card">
      <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
        <h4 class="project-title item">GTA V FiveM</h4>
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
          class="object-cover w-full h-48 md:h-96 rounded-lg"
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
      <div class="card-image bg-purple-600">
        <img
          class="object-cover w-full h-48 md:h-96 rounded-lg"
          src="https://user-images.githubusercontent.com/72839343/184925462-a15e69dc-de87-40ee-8c39-95452c84ddce.PNG"
        />
      </div>
    </div>
  </div>

  <div class="banner-1" id="testimonial">
    <div class="space-y-4 grid place-items-center mt-5">
      <h3 class="heading3 text-purple-900">Escrevendo minha história</h3>
      <p class="font-work_sans text-white font-semibold leading-relaxed">
        Conteúdo postado diretamente por mim!
      </p>
    </div>
    <div class="max-w-6xl mx-auto px-8 py-16">
      <div class="relative">
        <div class="relative lg:flex rounded-lg shadow-2xl overflow-hidden">
          <div
            class="h-56 lg:h-auto lg:w-5/12 relative flex items-center justify-center"
          >
            <img
              class="absolute h-full w-full object-cover"
              src="https://scontent.fcks1-1.fna.fbcdn.net/v/t1.6435-9/61728714_1217354208443906_7296813298878513152_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=8bfeb9&_nc_eui2=AeF3hxeQasj45tyDAVhxYwy2zUvQqwsPCPnNS9CrCw8I-XUF3gHMmD0D5k5eMhxjqphg7ErP1PLSgp55MV6CL8fF&_nc_ohc=JY_EWvzIHvkAX8YvW-t&tn=4f5QxD8Wb7_ajWu-&_nc_ht=scontent.fcks1-1.fna&oh=00_AT89YNSDtSzgqbT4C1RDxUGKRosY1H4Exy1JhUio8TdTww&oe=631F4AB2"
              alt=""
            />
            <div class="absolute inset-0 bg-gray-700 opacity-40"></div>
            <svg
              class="relative"
              width="100"
              height="50"
              viewBox="0 0 200 120"
            >
              <path
                fill="#fff"
                fill-rule="evenodd"
                d="M63.75 75.24l2.5-5.93c2.7 2.05 6.3 3.13 9.85 3.13 2.61 0 4.27-1.03 4.27-2.6-.04-4.37-15.7-.95-15.82-11.9-.04-5.58 4.8-9.86 11.66-9.86 4.08 0 8.16 1.03 11.06 3.38l-2.34 6.05c-2.66-1.73-5.97-2.97-9.12-2.97-2.13 0-3.55 1.03-3.55 2.36.04 4.28 15.82 1.94 15.98 12.4 0 5.7-4.72 9.69-11.5 9.69-4.96 0-9.52-1.2-12.99-3.75zm96.01-8.08a7.16 7.16 0 0 1-8.11 3.5 7.35 7.35 0 0 1-5.38-7.13c0-3.34 2.2-6.27 5.38-7.12 3.16-.85 6.5.58 8.11 3.5l6.9-3.93a15.02 15.02 0 0 0-17.03-7.42 15.42 15.42 0 0 0-11.33 14.97c0 7.04 4.66 13.2 11.33 14.97a15.02 15.02 0 0 0 17.04-7.43l-6.9-3.9zM91.71 35.25h8.64v43.16h-8.64V35.25zm78.34 0v43.16h8.65V65.48l10.25 12.93H200l-13.03-15.37 12.06-14.34h-10.58l-9.76 11.9V35.25h-8.64zm-43.82 31.1a8.14 8.14 0 0 1-6.83 3.56 7.24 7.24 0 0 1-7.33-7.16 7.24 7.24 0 0 1 7.33-7.15 8.1 8.1 0 0 1 6.83 3.67v7.08zm0-18v3.4c-1.43-2.36-5-4-8.72-4-7.7 0-13.76 6.64-13.76 14.96 0 8.33 6.07 15.04 13.76 15.04 3.73 0 7.3-1.63 8.72-4v3.4H135v-28.8h-8.77zM10.53 66.4A5.32 5.32 0 0 1 5.3 71.8 5.32 5.32 0 0 1 .04 66.4a5.32 5.32 0 0 1 5.25-5.38h5.25v5.38zm2.63 0a5.32 5.32 0 0 1 5.25-5.38c2.9 0 5.25 2.4 5.25 5.38v13.46a5.32 5.32 0 0 1-5.25 5.39 5.32 5.32 0 0 1-5.25-5.39V66.4zm5.26-21.63a5.32 5.32 0 0 1-5.25-5.38A5.32 5.32 0 0 1 18.42 34c2.9 0 5.25 2.41 5.25 5.39v5.38h-5.25zm0 2.74c2.9 0 5.25 2.41 5.25 5.39a5.32 5.32 0 0 1-5.25 5.38H5.25A5.32 5.32 0 0 1 0 52.9a5.32 5.32 0 0 1 5.25-5.39h13.17zm21.03 5.39a5.32 5.32 0 0 1 5.25-5.39c2.9 0 5.25 2.41 5.25 5.39a5.32 5.32 0 0 1-5.25 5.38h-5.25V52.9zm-2.62 0a5.32 5.32 0 0 1-5.25 5.38 5.32 5.32 0 0 1-5.25-5.38V39.39A5.32 5.32 0 0 1 31.58 34c2.9 0 5.25 2.41 5.25 5.39v13.5zm-5.25 21.58c2.9 0 5.25 2.41 5.25 5.38a5.32 5.32 0 0 1-5.25 5.39 5.32 5.32 0 0 1-5.25-5.39v-5.38h5.25zm0-2.7a5.32 5.32 0 0 1-5.25-5.38 5.32 5.32 0 0 1 5.25-5.38h13.17c2.9 0 5.25 2.4 5.25 5.38a5.32 5.32 0 0 1-5.25 5.39H31.58z"
              />
            </svg>
          </div>
          <div class="relative lg:w-7/12 bg-white">
            <svg
              class="absolute h-full text-white w-24 -ml-12"
              fill="currentColor"
              viewBox="0 0 100 100"
              preserveAspectRatio="none"
            >
              <polygon points="50,0 100,0 50,100 0,100" />
            </svg>
            <div
              class="relative py-12 lg:py-24 px-8 lg:px-16 text-gray-700 leading-relaxed"
            >
              <p>
                <strong class="text-black font-medium"> Desenvolvedor de software</strong>
                com 3 anos de experiência na função de freelancer. Trabalhando com  <strong class="text-black font-medium">HTML,CSS e JS.</strong>  2 anos e meio de experiência com <strong class="text-black font-medium">Vue.JS e Node.JS.</strong> Além disso, também trabalho com <strong class="text-black font-medium">Design UI | UX</strong> utilizando Figma, ademais gosto de contribuir em canais de voz como “Discord” tirando dúvidas de alguns devs. Também gosto de utilizar plataforma para versionamento de código: GIT, GitHub e Vercel. <br><br>

                <strong class="text-black font-medium" style="font-size:12px">MAESTRIAS &rarr;</strong><a href="/" class="text-gray-500 font-medium" style="font-size:12px"> HTML | CSS | JS | PHP | C++ | NODE.JS | VUE.JS | BOOTSTRAP | GIT | GITHUB | UI-UX | CLEAN CODE | PATTERN | KANBAN | SCRUM </a> 
              </p>
              <p class="mt-6">
                <a href="/">Autor</a>
                <a
                  href="https://www.linkedin.com/in/leoscastro/"
                  target="_blank"
                  class="font-medium text-purple-600 hover:text-indigo-900"
                >
                  &rarr; Leonardo Silva Castro 🥇</a
                >
              </p>
            </div>
          </div>
        </div>
        <!--
        <div class="absolute inset-y-0 left-0 lg:flex lg:items-center">
          <button
            class="mt-24 lg:mt-0 -ml-6 h-12 w-12 rounded-full bg-white p-3 shadow-lg"
          >
            <svg
              class="h-full w-full text-indigo-900"
              fill="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                d="M5.41 11H21a1 1 0 0 1 0 2H5.41l5.3 5.3a1 1 0 0 1-1.42 1.4l-7-7a1 1 0 0 1 0-1.4l7-7a1 1 0 0 1 1.42 1.4L5.4 11z"
              />
            </svg>
          </button>
        </div>
        <div class="absolute inset-y-0 right-0 lg:flex lg:items-center">
          <button
            class="mt-24 lg:mt-0 -mr-6 h-12 w-12 rounded-full bg-white p-3 shadow-lg"
          >
            <svg
              class="h-full w-full text-indigo-900"
              fill="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                d="M18.59 13H3a1 1 0 0 1 0-2h15.59l-5.3-5.3a1 1 0 1 1 1.42-1.4l7 7a1 1 0 0 1 0 1.4l-7 7a1 1 0 0 1-1.42-1.4l5.3-5.3z"
              />
            </svg>
          </button>
        </div>
        -->
      </div>
    </div>
  </div>

  <div class="banner-2 md:flex items-center md:justify-evenly" id="about">
    <img
      class="md:h-[500px] h-[400px] rounded-lg"
      src="https://c.tenor.com/YNevMW28IysAAAAi/hacker-friend.gif"
      alt="user image"
    />
    <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-2/2">
      <h4 class="project-title item">Minha visão de trabalho?</h4>
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
        Sempre gosto de passar minha visão, dar minha opnião sobre o que estamos 
        construindo e qual seria a melhor forma de encontrarmos a solução. 
      </p>
      <button class="text-black font-bold text-1xl tracking-wider">
        Volte sempre &rarr; #user
      </button>
    </div>
  </div>

  <div class="banner-1 flex h-full items-center">
    <div class="w-7/12 p-12">
      <h2 class="text-purple-500 md:text-6xl text-2xl mb-5 font-bold">
        Vamos trabalhar juntos e deixar tudo comentado e limpo!
      </h2>
      <a class="none text-2xl text-white"
        >🏆castroz.dev@gmail.com</a
      >
    </div>
    <div class="w-5/12 pr-28 footer">
      <div class="flex flex-wrap justify-end gap-2">
        <a href="https://github.com/leocastroz" target="_blank" class="bg-black-400 p-2 font-semibold text-white inline-flex items-center space-x-2 rounded">
           
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 0C5.37 0 0 5.37 0 12C0 17.31 3.435 21.795 8.205 23.385C8.805 23.49 9.03 23.13 9.03 22.815C9.03 22.53 9.015 21.585 9.015 20.58C6 21.135 5.22 19.845 4.98 19.17C4.845 18.825 4.26 17.76 3.75 17.475C3.33 17.25 2.73 16.695 3.735 16.68C4.68 16.665 5.355 17.55 5.58 17.91C6.66 19.725 8.385 19.215 9.075 18.9C9.18 18.12 9.495 17.595 9.84 17.295C7.17 16.995 4.38 15.96 4.38 11.37C4.38 10.065 4.845 8.985 5.61 8.145C5.49 7.845 5.07 6.615 5.73 4.965C5.73 4.965 6.735 4.65 9.03 6.195C9.99 5.925 11.01 5.79 12.03 5.79C13.05 5.79 14.07 5.925 15.03 6.195C17.325 4.635 18.33 4.965 18.33 4.965C18.99 6.615 18.57 7.845 18.45 8.145C19.215 8.985 19.68 10.05 19.68 11.37C19.68 15.975 16.875 16.995 14.205 17.295C14.64 17.67 15.015 18.39 15.015 19.515C15.015 21.12 15 22.41 15 22.815C15 23.13 15.225 23.505 15.825 23.385C18.2073 22.581 20.2775 21.05 21.744 19.0076C23.2106 16.9653 23.9996 14.5144 24 12C24 5.37 18.63 0 12 0Z" fill="white"/>
        </svg>

        </a>

        <a href="https://vercel.com/surinoto" target="_blank" class="bg-black-400 p-2 font-semibold text-white inline-flex items-center space-x-2 rounded">
            <svg width="24" height="21" viewBox="0 0 24 21" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M12 0L24 21H0L12 0Z" fill="white"/>
            </svg>
       
        </a>


        <a href="https://www.facebook.com/LeonardoCastro.Leoneell/" target="_blank" class="bg-black-400 p-2 font-semibold text-white inline-flex items-center space-x-2 rounded">
           
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M0 12.067C0 18.033 4.333 22.994 10 24V15.333H7V12H10V9.333C10 6.333 11.933 4.667 14.667 4.667C15.533 4.667 16.467 4.8 17.333 4.933V8H15.8C14.333 8 14 8.733 14 9.667V12H17.2L16.667 15.333H14V24C19.667 22.994 24 18.034 24 12.067C24 5.43 18.6 0 12 0C5.4 0 0 5.43 0 12.067Z" fill="white"/>
        </svg>

       
        </a>


        <a href="https://www.linkedin.com/in/leoscastro/" target="_blank" class="bg-black-400 p-2 font-semibold text-white inline-flex items-center space-x-2 rounded">
                  
        <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M2.7206e-07 1.838C2.7206e-07 1.35053 0.193646 0.883032 0.538338 0.53834C0.88303 0.193648 1.35053 2.45031e-06 1.838 2.45031e-06H20.16C20.4016 -0.000392101 20.6409 0.0468654 20.8641 0.139069C21.0874 0.231273 21.2903 0.366612 21.4612 0.537339C21.6322 0.708065 21.7677 0.910826 21.8602 1.13401C21.9526 1.3572 22.0001 1.59643 22 1.838V20.16C22.0003 20.4016 21.9529 20.6409 21.8606 20.8642C21.7683 21.0875 21.6328 21.2904 21.462 21.4613C21.2912 21.6322 21.0884 21.7678 20.8651 21.8602C20.6419 21.9526 20.4026 22.0001 20.161 22H1.838C1.59655 22 1.35746 21.9524 1.1344 21.86C0.911335 21.7676 0.708671 21.6321 0.537984 21.4613C0.367297 21.2905 0.231932 21.0878 0.139623 20.8647C0.0473133 20.6416 -0.000131096 20.4025 2.7206e-07 20.161V1.838ZM8.708 8.388H11.687V9.884C12.117 9.024 13.217 8.25 14.87 8.25C18.039 8.25 18.79 9.963 18.79 13.106V18.928H15.583V13.822C15.583 12.032 15.153 11.022 14.061 11.022C12.546 11.022 11.916 12.111 11.916 13.822V18.928H8.708V8.388ZM3.208 18.791H6.416V8.25H3.208V18.79V18.791ZM6.875 4.812C6.88105 5.08667 6.83217 5.35979 6.73124 5.61532C6.63031 5.87084 6.47935 6.10364 6.28723 6.30003C6.09511 6.49643 5.8657 6.65248 5.61246 6.75901C5.35921 6.86554 5.08724 6.92042 4.8125 6.92042C4.53776 6.92042 4.26579 6.86554 4.01255 6.75901C3.7593 6.65248 3.52989 6.49643 3.33777 6.30003C3.14565 6.10364 2.99469 5.87084 2.89376 5.61532C2.79283 5.35979 2.74395 5.08667 2.75 4.812C2.76187 4.27286 2.98439 3.75979 3.36989 3.38269C3.75539 3.00558 4.27322 2.79442 4.8125 2.79442C5.35178 2.79442 5.86961 3.00558 6.25512 3.38269C6.64062 3.75979 6.86313 4.27286 6.875 4.812V4.812Z" fill="white"/>
        </svg>
              
        </a>


        <a href="https://api.whatsapp.com/send?phone=+5594992195331&text=Olá! Leonardo Castro" target="_blank" class="bg-black-400 p-2 font-semibold text-white inline-flex items-center space-x-2 rounded">
                    
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g clip-path="url(#clip0_160_8)">
        <path fill-rule="evenodd" clip-rule="evenodd" d="M17.415 14.382C17.117 14.233 15.656 13.515 15.384 13.415C15.112 13.316 14.914 13.267 14.715 13.565C14.517 13.861 13.948 14.531 13.775 14.729C13.601 14.928 13.428 14.952 13.131 14.804C12.834 14.654 11.876 14.341 10.741 13.329C9.858 12.541 9.261 11.568 9.088 11.27C8.915 10.973 9.069 10.812 9.218 10.664C9.352 10.531 9.515 10.317 9.664 10.144C9.813 9.97004 9.862 9.84604 9.961 9.64704C10.061 9.44904 10.011 9.27604 9.936 9.12704C9.862 8.97804 9.268 7.51504 9.02 6.92004C8.779 6.34104 8.534 6.42004 8.352 6.41004C8.178 6.40204 7.98 6.40004 7.782 6.40004C7.584 6.40004 7.262 6.47404 6.99 6.77204C6.717 7.06904 5.95 7.78804 5.95 9.25104C5.95 10.713 7.014 12.126 7.163 12.325C7.312 12.523 9.258 15.525 12.239 16.812C12.949 17.118 13.502 17.301 13.933 17.437C14.645 17.664 15.293 17.632 15.805 17.555C16.375 17.47 17.563 16.836 17.811 16.142C18.058 15.448 18.058 14.853 17.984 14.729C17.91 14.605 17.712 14.531 17.414 14.382H17.415ZM11.993 21.785H11.989C10.2184 21.7854 8.48037 21.3094 6.957 20.407L6.597 20.193L2.855 21.175L3.854 17.527L3.619 17.153C2.62914 15.5774 2.10529 13.7538 2.108 11.893C2.11 6.44304 6.544 2.00904 11.997 2.00904C14.637 2.00904 17.119 3.03904 18.985 4.90704C19.9054 5.82362 20.6349 6.91361 21.1313 8.11394C21.6277 9.31427 21.8811 10.6011 21.877 11.9C21.875 17.35 17.441 21.785 11.993 21.785V21.785ZM20.405 3.48804C19.3032 2.37896 17.9922 1.49958 16.5481 0.900841C15.1039 0.302105 13.5553 -0.00407625 11.992 4.09775e-05C5.438 4.09775e-05 0.102 5.33504 0.1 11.892C0.096963 13.9788 0.644374 16.0294 1.687 17.837L0 24L6.304 22.346C8.04787 23.2962 10.0021 23.794 11.988 23.794H11.993C18.547 23.794 23.883 18.459 23.885 11.901C23.8898 10.3383 23.5848 8.79014 22.9874 7.34607C22.3901 5.90201 21.5124 4.59071 20.405 3.48804" fill="white"/>
        </g>
        <defs>
        <clipPath id="clip0_160_8">
        <rect width="24" height="24" fill="white"/>
        </clipPath>
        </defs>
        </svg>
       
        </a>


    
        
        
      </div>
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

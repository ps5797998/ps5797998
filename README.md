<!doctype html>
<html class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="shortcut icon" href="logo.png" type="image/x-icon">
  <title>Abhishek yadav</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .back{
      background-image: url('./bg.png');
      background-size: cover;
      height: 100vh;
    }
    .gradient{
      background: rgb(17,24,39);
      background: linear-gradient(0deg, rgba(17,24,39,1) 6%, rgba(18,22,31,1) 54%, rgba(20,20,21,1) 93%);;
    }
  </style>
</head>
<body class=" bg-gray-900">
  <!-- Header -->
  <section class="back">
  <header class="text-gray-400 body-font" id="main">
    <div class="container mx-auto flex flex-wrap flex-col md:flex-row items-center">
      <a href="#main" class="flex title-font font-medium items-center text-white mb-4 md:mb-0 cursor-pointer">
        <img src="logo.png" class="w-24 h-24" >
         <!-- <span class="ml-3 text-xl">Abhishek yadav</span> -->
     </a>
      <nav class="md:ml-auto md:mr-auto flex flex-wrap items-center text-base justify-center">

      </nav>

      <a href="#contact-me">
        <button class="inline-flex items-center border-0 py-1 px-3 focus:outline-none bg-gray-700 rounded text-base mt-4 md:mt-0 hidden mr-3 hover:bg-gray-400 text-white sm:flex">Contact
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
            <path d="M5 12h14M12 5l7 7-7 7"></path>
          </svg>
        </button>
      </a>
    </div>
  </header>

  <!--  Hero --> 
  <section class="text-gray-400  body-font">
    <div class="container mx-auto flex px-5 py-4 sm:py-24 md:flex-row flex-col items-center ">
      <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
        <h2 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-white">Hello, I am <span class="text-green-400"> Abhishek </span></h2>
            <h1 class="title-font sm:text-3xl text-2xl mb-4 font-medium text-white">Bringing Ideas to Life with Innovative <br class="hidden lg:inline-block">  Web Solutions</h1>
            <p class="leading-relaxed mb-8">As a Web developer, I'm constantly exploring new ways <br class="hidden lg:inline-block"> to bring ideas to life. With a passion for creativity and a  deep understanding <br class="hidden lg:inline-block">of technology,  I'm able to transform complex concepts into real-world solutions <br class="hidden lg:inline-block"> that make a difference. </p>
            <div class="flex justify-center">
              <a href="https://resumeismy.netlify.app/" target="_blank">
                <button class="inline-flex text-white bg-green-500 border-0 py-2 px-6 focus:outline-none hover:bg-green-600 rounded text-lg" >Resume</button>
              </a>
              <a href="#contact-me">
                <button class="ml-4 inline-flex text-gray-400 bg-gray-800 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg">Contact</button>
              </a>
            </div>
      </div>
    </div>
  </section>

</section>
 

<!-- Features -->

<section class="text-gray-400 gradient body-font">
    <div class="container py-4 sm:py-24 mx-auto flex flex-wrap">
        <div class="flex flex-col flex-wrap lg:py-6 -mb-10 lg:w-1/2 lg:pl-12 lg:text-left text-center">
          <h1 class="sm:text-3xl text-2xl font-medium title-font mb-14 text-white">Transforming Complex Ideas into Simple, Impactful Web Solutions</h1>
        <div class="flex flex-col mb-10 lg:items-start items-center">
          <div class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-gray-800 text-green-400 mb-5">
            <img src="js.png" class="w-6 h-6 rounded-full" >
          </div>
        
      </div>
      <div class="lg:w-1/2 w-full mb-10  lg:mb-0 rounded-lg overflow-hidden">
        <img alt="feature" class=" object-center ml-0 mt-10 sm:ml-6 sm:mt-0  " src="me1.png">
      </div>
    </div>
  </section>

 <!-- Computer langugae worked earler -->

 <section class="text-gray-400 body-font bg-gray-900">
    <div class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap w-full mb-20 flex-col items-center text-center">
        <h1 class="sm:text-3xl text-2xl font-medium title-font mb-2 text-white">Skills and Expertise in Various Technologies</h1>
        <p class="lg:w-1/2 w-full leading-relaxed text-opacity-80">With years of experience in the tech industry, I've developed a broad skill set and expertise in various programming languages and technologies.</p>
      </div>
      <div class="flex flex-wrap -m-4">
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="border border-gray-700 border-opacity-75 p-6 rounded-lg">
            <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-gray-800 text-green-400 mb-4">
                <img src="sc.png" class="w-6 h-6 rounded-full" >
            </div>
            <h2 class="text-lg text-white font-medium title-font mb-2">HTML</h2>
            <p class="leading-relaxed text-base">As a front-end developer, I've used HTML to structure and organize content on the web, creating clean and semantic markup for optimal accessibility and SEO..</p>
          </div>
        </div>
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="border border-gray-700 border-opacity-75 p-6 rounded-lg">
            <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-gray-800 text-green-400 mb-4">
                <img src="css.png" class="w-6 h-6 rounded-full" >
            </div>
            <h2 class="text-lg text-white font-medium title-font mb-2">CSS</h2>
            <p class="leading-relaxed text-base">I'm proficient in using CSS to style web pages, creating beautiful and responsive layouts that adapt to different screen sizes and devices..</p>
          </div>
        </div>
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="border border-gray-700 border-opacity-75 p-6 rounded-lg">
            <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-gray-800 text-green-400 mb-4">
                <img src="js.png" class="w-6 h-6 rounded-full" >
            </div>
            <h2 class="text-lg text-white font-medium title-font mb-2">JavaScript</h2>
            <p class="leading-relaxed text-base">With a deep understanding of JavaScript fundamentals, I'm able to build dynamic and interactive web applications that provide a seamless user experience.</p>
          </div>
        </div>
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="border border-gray-700 border-opacity-75 p-6 rounded-lg">
            <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-gray-800 text-green-400 mb-4">
                <img src="react.png" class="w-6 h-6 rounded-full" >
            </div>
           
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="border border-gray-700 border-opacity-75 p-6 rounded-lg">
            <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-gray-800 text-green-400 mb-4">
                <img src="python.png" class="w-6 h-6 rounded-full" >
            </div>
            <h2 class="text-lg text-white font-medium title-font mb-2">Python</h2>
            <p class="leading-relaxed text-base">I'm proficient in using Python to build robust and scalable software solutions, leveraging its versatility and readability to create efficient and elegant code.</p>
          </div>
        </div>
        <div class="xl:w-1/3 md:w-1/2 p-4">
          <div class="border border-gray-700 border-opacity-75 p-6 rounded-lg">
            <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-gray-800 text-green-400 mb-4">
                <img src="db.png" class="w-6 h-6 rounded-full" >
            </div>
            <h2 class="text-lg text-white font-medium title-font mb-2">SQL Database</h2>
            <p class="leading-relaxed text-base">With a strong understanding of relational database concepts and SQL syntax, I'm able to design and manage complex database schemas and queries.</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  

  <!-- Blogs -->

  <section class="text-gray-400 bg-gray-900 body-font overflow-hidden">
    <div class="container px-5 py-24 mx-auto">
      <h1 class="sm:text-3xl text-2xl font-medium text-center title-font mb-24 text-white">Some of my Insights.</h1>
      <div class="flex flex-wrap -m-12">
        <div class="p-12 md:w-1/2 flex flex-col items-start">
        
          <div class="flex items-center flex-wrap pb-4 mb-4 border-b-2 border-gray-800 border-opacity-75 mt-auto w-full">
            <a class="text-green-400 inline-flex items-center" target="_blank" href="https://mail.google.com/mail/u/0/#inbox">Read More
              <svg class="w-4 h-4 ml-2" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path d="M5 12h14"></path>
                <path d="M12 5l7 7-7 7"></path>
              </svg>
            </a>
            <span class="text-gray-500 mr-3 inline-flex items-center ml-auto leading-none text-sm pr-3 py-1 border-r-2 border-gray-800">
              <svg class="w-4 h-4 mr-1" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
                <path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"></path>
                <circle cx="12" cy="12" r="3"></circle>
              </svg>1.2K
            </span>
            <span class="text-gray-500 inline-flex items-center leading-none text-sm">
              <svg class="w-4 h-4 mr-1" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
                <path d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"></path>
              </svg>6
            </span>
          </div>
        </div>
        <div class="p-12 md:w-1/2 flex flex-col items-start">
          <span class="inline-block py-1 px-2 rounded bg-gray-800 text-gray-400 text-opacity-75 text-xs font-medium tracking-widest">CONTENT WRITING</span>
          <h2 class="sm:text-3xl text-2xl title-font font-medium text-white mt-4 mb-4">Homeschooling in India</h2>
          <p class="leading-relaxed mb-8">Homeschooling fills a gap of traditional education system. As subject are more specific the child has more access of knowledge in a particular field. Homeschooled student’s performance is much better than their counterpart studying in traditional schools.</p>
          <div class="flex items-center flex-wrap pb-4 mb-4 border-b-2 border-gray-800 border-opacity-75 mt-auto w-full">
            <a class="text-green-400 inline-flex items-center" target="_blank" href="https://mail.google.com/mail/u/0/#inbox">Read More
              <svg class="w-4 h-4 ml-2" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path d="M5 12h14"></path>
                <path d="M12 5l7 7-7 7"></path>
              </svg>
            </a>
            <span class="text-gray-500 mr-3 inline-flex items-center ml-auto leading-none text-sm pr-3 py-1 border-r-2 border-gray-800">
              <svg class="w-4 h-4 mr-1" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
                <path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"></path>
                <circle cx="12" cy="12" r="3"></circle>
              </svg>1.2K
            </span>
            <span class="text-gray-500 inline-flex items-center leading-none text-sm">
              <svg class="w-4 h-4 mr-1" stroke="currentColor" stroke-width="2" fill="none" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24">
                <path d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"></path>
              </svg>6
            </span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->

  <section class="text-gray-400 bg-gray-900 body-font relative" id="contact-me">
    <div class="container px-5 pt-24 mx-auto flex sm:flex-nowrap flex-wrap">
      <div class="lg:w-2/3 md:w-1/2 bg-gray-900 rounded-lg overflow-hidden sm:mr-10 p-10 flex items-end justify-start relative">
        <iframe width="100%" height="100%" title="map" class="absolute inset-0" frameborder="0" marginheight="0" marginwidth="0" scrolling="no" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d241317.14571380627!2d72.71637378187377!3d19.082177513076093!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3be7c6306644edc1%3A0x5da4ed8f8d648c69!2sMumbai%2C%20Maharashtra!5e0!3m2!1sen!2sin!4v1683103142361!5m2!1sen!2sin" style="filter: grayscale(1) contrast(1.2) opacity(0.16);"></iframe>
        <div class="bg-gray-900 relative flex flex-wrap py-6 rounded shadow-md">
          <div class="lg:w-1/2 px-6">
            <h2 class="title-font font-semibold text-white tracking-widest text-xs">ADDRESS</h2>
            <p class="mt-1">Mumbai, Maharashtra, India</p>
          </div>
          <div class="lg:w-1/2 px-6 mt-4 lg:mt-0 cursor-pointer">
            <h2 class="title-font font-semibold text-white tracking-widest text-xs">EMAIL</h2>
            <a class="text-green-400 leading-relaxed">AY397473@GMAIL.COM</a>
          </div>
        </div>
      </div>
      <div class="lg:w-1/3 md:w-1/2 flex flex-col md:ml-auto w-full md:py-8 mt-8 md:mt-0">
        <h2 class="text-white  mb-1 text-2xl font-medium title-font">Let's Connect</h2>
        <p class="leading-relaxed mb-5">Let's Connect and Create Something Amazing Together</p>
        <div class="relative mb-4">
          <label for="name" class="leading-7 text-sm text-gray-400">Name</label>
          <input type="text" id="name" name="name" class="w-full bg-gray-800 rounded border border-gray-700 focus:border-green-500 focus:ring-2 focus:ring-green-900 text-base outline-none text-gray-100 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
        </div>
        <div class="relative mb-4">
          <label for="email" class="leading-7 text-sm text-gray-400">Email</label>
          <input type="email" id="email" name="email" class="w-full bg-gray-800 rounded border border-gray-700 focus:border-green-500 focus:ring-2 focus:ring-green-900 text-base outline-none text-gray-100 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
        </div>
        <div class="relative mb-4">
          <label for="message" class="leading-7 text-sm text-gray-400">Message</label>
          <textarea id="message" name="message" class="w-full bg-gray-800 rounded border border-gray-700 focus:border-green-500 focus:ring-2 focus:ring-green-900 h-32 text-base outline-none text-gray-100 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
        </div>
        <button class="text-white bg-green-500 border-0 py-2 px-6 focus:outline-none hover:bg-green-600 rounded text-lg">Connect</button>
        <p class="text-xs text-gray-400 text-opacity-90 mt-3">I will connect to you as soon as possible.</p>
      </div>
    </div>
  </section>

  <!-- Footer -->

  <footer class="text-gray-400 bg-gray-900 body-font">
    <div class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col">
      <a href="#main" class="flex title-font font-medium items-center md:justify-start justify-center text-white">
        <img src="logo.png" class="w-10 h-10 rounded-full" >
        <span class="ml-3 text-xl">Gaurav Pandey</span>
      </a>
      <p class="text-sm text-gray-400 sm:ml-4 sm:pl-4 sm:border-l-2 sm:border-gray-800 sm:py-2 sm:mt-0 mt-4">© 2023 Gaurav Pandey —
        <a href="https://twitter.com/GauravPandey04" class="text-gray-500 ml-1" target="_blank" rel="noopener noreferrer">@gauravpandey</a>
      </p>
      
        <a class="ml-3 text-gray-400" target="_blank" href="https://www.instagram.com/abhishekyadav_____01/#">
          <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
            <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
            <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
          </svg>
        </a>
        <a class="ml-3 text-gray-400" target="_blank" href="https://www.linkedin.com/in/abhishek-yaduvanshi-1a9283208/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3BIlTBfuUvQsSGQsbRFb%2BWVA%3D%3D">
          <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
            <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"></path>
            <circle cx="4" cy="4" r="2" stroke="none"></circle>
          </svg>
        </a>
      </span>
    </div>
  </footer>

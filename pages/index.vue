<template>
<div class="z-20 top-0 h-[108px] flex items-center bg-[#151A2F] px-[70px] py-3 sticky">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
  <div class="max-w-[1220px] px-[10px] w-full m-auto flex justify-between items-center">
    <img src="/images/x-tech_logo.png" alt="Logo" class="h-10">
    <div class="flex space-x-6 text-white justify-between lg:justify-around">
      <p class="hidden lg:flex items-center font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
        <span>HOME</span>
        <img src="/images/arrow_down.svg" alt="Arrow Down" class="w-4 h-4">
      </p>
      <p class="hidden lg:flex items-center font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
        <span>ABOUT</span>
        <img src="/images/arrow_down.svg" alt="Arrow Down" class="w-4 h-4">
      </p>
      <p class="hidden lg:flex items-center font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
        <span>ROAD MAP</span>
        <img src="/images/arrow_down.svg" alt="Arrow Down" class="w-4 h-4">
      </p>
      <p class="hidden lg:flex items-center font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
        <span>NFT</span>
        <img src="/images/arrow_down.svg" alt="Arrow Down" class="w-4 h-4">
      </p>
      <p class="hidden lg:flex items-center font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
        <span>BLOG</span>
        <img src="/images/arrow_down.svg" alt="Arrow Down" class="w-4 h-4">
      </p>
      <p class="hidden lg:flex  cursor-pointer font-bold text-xl hover:text-[#16C2A3]">CONTACT</p>
    </div>
    <button class="group relative w-[140px] p-4 text-center uppercase font-black bg-transparent overflow-hidden transition-shadow duration-500">
      <span class="text-white relative z-10">CONTACT US</span>
      <span class="absolute inset-x-0 bottom-0 h-1 bg-transparent border-b-4 border-l-4 border-transparent transform translate-x-full transition-all duration-300 group-hover:border-[#16C2A3] group-hover:translate-x-0 group-hover:h-full"></span>
      <span class="absolute inset-x-0 top-0 h-1 bg-transparent border-t-4 border-r-4 border-transparent transform -translate-x-full transition-all duration-300 group-hover:border-[#16C2A3] group-hover:translate-x-0 group-hover:h-full delay-300"></span>
    </button>
    <div class="lg:hidden">
      <img @click="open()" class="h-[40px] cursor-pointer" src="/images/menu.png" alt="Menu Logo">
      <div v-if="menu === true" class="absolute top-0 left-0 z-[999999] p-[10px]  w-[40%]  h-[1000vh] bg-[#100d1e]">
        <p class="p-[10px] text-white font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
          <span>BLOG</span>
        </p>
        <p class="p-[10px] text-white font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
          <span>ABOUT</span>
        </p>
        <p class="p-[10px] text-white font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
          <span>ROAD MAP</span>
        </p>
        <p class="p-[10px] text-white font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
          <span>NFT</span>
        </p>
        <p class="p-[10px] text-white font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
          <span>BLOG</span>
        </p>
        <p class="p-[10px] text-white font-bold text-xl space-x-2 cursor-pointer hover:text-[#16C2A3]">
          <span>CONTACT</span>
        </p>
      </div>
    </div>
  </div>
</div>
  <div
      class="bg-cover bg-center md:bg-[url('/images/test.png')] bg-[#151A2F] py-[50px] md:py-[90px] px-[20px]"
  >
    <div class="bg-multi-bg max-w-[1200px] w-full m-auto">
      <h1 class="text-white text-2xl md:text-4xl mb-[16px] md:mb-[24px] font-bold">
        FUELING FOUNDER-LED DISRUPTION
      </h1>
      <p class="text-white text-base md:text-2xl mb-[16px] md:mb-[24px]">
        We are a pre-seed venture studio with a mission to support
        global non-tech founders by providing CTO-level expertise and
        rapid MVP development, leveraging 16+ years of experience and
        300 successful projects.
      </p>
      <button
          class="cursor-pointer text-white font-bold text-sm md:text-xl bg-[#16C2A3] py-[10px] md:py-[12px] px-[20px] md:px-[24px]"
      >
        BOOK A FREE CONSULTATION
      </button>
    </div>
  </div>
  <div class="bg-[#061023] py-14 pt-14 pb-20  px-[50px]">
    <asd />
  </div>
<div class="bg-[#151A2F] py-[74px]">
  <h1 class="text-white text-center font-bold mb-[44px] md:text-3xl lg:text-6xl text-xl">
    Innovative Support for Industry Champions
    </h1>
  <div class="max-w-[1396px] px-[10px] w-full mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-[20px]">
    <div class="bg-[#13222F] border-2 border-[#5ABFA4] flex flex-col items-center justify-center p-7 ">
      <img src="/images/frame.png" alt="" class="mb-4">
        <h1 class="text-xl text-center text-white mb-[10px]">
        INVESTING IN NON-TECH FOUNDERS
      </h1>
      <p class="text-white text-center">
        At X-TECH, we partner with non-tech experts,
        empowering them to innovate in AR, VR, and AI
        by becoming their technical co-founders.
      </p>
    </div>
    <div class="bg-[#13222F] border-2 border-[#5ABFA4] flex flex-col items-center justify-center p-7 ">
      <img src="/images/vector.png" alt="" class="mb-4">
      <h1 class="text-xl text-center text-white mb-[10px]">
        AR & VR + AI DOMAIN
      </h1>
      <p class="text-white text-center">
        Specializing in AR, VR, and AI, we enable founders
        to disrupt industries quickly by leveraging our
        existing R&D-driven tech stack for faster, more
        efficient development.
      </p>
    </div>
    <div class="bg-[#13222F] border-2 border-[#5ABFA4] flex flex-col items-center justify-center p-7 ">
      <img src="/images/cost_savings.png" alt="" class="mb-4">
      <h1 class="text-xl text-center text-white mb-[10px]">
        WE BECOME YOUR CTOs
      </h1>
      <p class="text-white text-center">
        We step in as hands-on CTOs, offering
        strategic guidance and cutting-edge
        tech expertise to bring your vision
        to life.
      </p>
    </div>
    <div class="bg-[#13222F] border-2 border-[#5ABFA4] flex flex-col items-center justify-center p-7 ">
      <img src="/images/flexibility_scalability.png" alt="" class="mb-4">
      <h1 class="text-xl text-center text-white mb-[10px]">
        INVESTING WITH TECH
      </h1>
      <p class="text-white text-center">
        X-TECH invests in tech-driven solutions
        for non-tech founders, ensuring your
        innovation is backed by robust technical
        foundations.
      </p>
    </div>
    <div class="bg-[#13222F] border-2 border-[#5ABFA4] flex flex-col items-center justify-center p-7 ">
      <img src="/images/remote_staffing_redefined.png" alt="" class="mb-4">
      <h1 class="text-xl text-center text-white mb-[10px]">
        EXPERTS LEADING THE WAY
      </h1>
      <p class="text-white text-center">
        We invest in industry champions,
        leveraging their deep expertise and
        our technical capabilities to drive
        impactful innovation.
      </p>
    </div>
    <div class=" w-full bg-[#13222F] border-2   border-[#5ABFA4] flex flex-col items-center justify-center p-7 ">
      <img src="/images/success_starts_here.png" alt="" class="mb-4">
      <h1 class="text-xl text-center text-white mb-[10px]">
        FUNDRAISING FOR 2024 GROWTH
      </h1>
      <p class="text-white text-center">
        X-TECH is raising funds in 2024
        to accelerate our mission of
        empowering non-tech founders
        with AR, VR, and AI solutions.
      </p>
    </div>
  </div>
</div>
<div class="py-[74px] bg-[#0c1226]">
  <h1 class="text-white  text-center font-bold mb-[24px] md:text-4xl lg:text-6xl text-3xl">
    Our Process
  </h1>
  <div class="flex items-center justify-center">
    <p class="max-w-[708px] px-[10px] w-[100%] text-white flex items-center justify-center mb-[46px]">
      We empower founders to focus on
      what matters—fundraising and business
      growth—while we handle the entire tech
      process.
    </p>
  </div>
  <div class="max-w-[1154px] gap-x-[100px] w-full px-[10px] m-auto flex">
    <div class="max-w-[13px] w-full lg:block hidden">
      <img src="/images/line.png" class="w-full h-full" alt="">
    </div>
    <div class="flex flex-col ">
      <div>
        <h1 class="text-white font-bold text-xl mb-[25px]">1. Founder FiT</h1>
        <p class="text-white mb-[30px]">
          We assess your expertise, the problem you’re
          solving, and why you’re the best to solve it.
          Ideal candidates can secure initial funding,
          demonstrating future fundraising potential.
        </p>
      </div>
      <div>
        <h1 class="text-white font-bold text-xl mb-[25px]">2. MVP Definition & Development</h1>
        <p class="text-white mb-[30px]">
          We define the MVP, estimate costs, agree on
          terms, appoint a CTO, and build it using our tech stack.
          Leveraging our 16 years of expertise and existing tech
          assets, we make development highly affordable and quick.
        </p>
      </div>
      <div>
        <h1 class="text-white font-bold text-xl mb-[20px]">3. MVP Delivery & Growth</h1>
        <p class="text-white mb-[30px]">
          After delivering the MVP, we help you showcase
          it through events and demos to prepare for the next
          round of funding together.
        </p>
      </div>
    </div>
  </div>
</div>
<div class="py-[74px] bg-[#151A2F]">
 <h1 class="text-white  text-center font-bold mb-[74px] md:text-3xl lg:text-6xl text-xl">
   Our Portfolio: Founders in Action
 </h1>
<flicking-component/>
</div>
  <div class="bg-[#0c1226] w-full flex flex-col md:flex-row gap-[30px] lg:gap-[100px]">
    <div class="py-[40px] md:py-[74px] px-[10px] w-full flex flex-col items-end">
      <div class="max-w-[687px] w-full">
        <h1 class="text-white text-4xl md:text-5xl lg:text-6xl font-bold mb-[20px] md:mb-[33px]">
          WHY CHOOSE US ?
        </h1>
        <p class="text-white max-w-[687px] flex items-center mb-[15px] md:mb-[19px]">
          At X-TECH Venture Studio, we believe true innovation
          comes from the founders themselves, not from imposing
          ideas and hoping for long-term passion. Our approach
          focuses on empowering founders to drive their visions.
        </p>
        <div class="bg-white h-[2px] mb-[30px] md:mb-[49px]"></div>
        <h1 class="text-white text-2xl md:text-3xl lg:text-4xl font-bold mb-[20px] md:mb-[34px]">
          Book the date for a free consultation
        </h1>
        <p class="text-white text-xl md:text-2xl font-bold mb-[30px] md:mb-[40px] flex justify-center">
          Select Day
        </p>
        <div class="flex items-center justify-center">
          <calendar-component />
        </div>
      </div>
    </div>
    <div class="my-[40px] md:my-[100px] lg:my-[159px] px-[10px] w-full grid gap-[20px] md:gap-[28px]">
      <div class="p-[20px] md:p-[30px] bg-[#13222F] border-2 border-[#5ABFA4] max-w-[823px]">
        <h1 class="text-lg md:text-xl text-white font-bold mb-[10px]">Team Stability</h1>
        <p class="mb-[10px] text-white">
          Startups often fail when a CTO leaves. At X-TECH,
          we have a team of experts, ensuring seamless
          transitions when needed.
        </p>
      </div>
      <div class="p-[20px] md:p-[30px] bg-[#13222F] border-2 border-[#5ABFA4] max-w-[823px]">
        <h1 class="text-lg md:text-xl text-white font-bold mb-[10px]">R&D Advantage</h1>
        <p class="mb-[10px] text-white">
          With 16 years of experience,
          we may already have the technology,
          reducing costs for startups.
        </p>
      </div>
      <div class="p-[20px] md:p-[30px] bg-[#13222F] border-2 border-[#5ABFA4] max-w-[823px]">
        <h1 class="text-lg md:text-xl text-white font-bold mb-[10px]">Cost Efficiency</h1>
        <p class="mb-[10px] text-white">
          Unlike typical tech teams that burn
          money, we step back after delivering
          the MVP, costing nothing until the
          founder raises funds.
        </p>
      </div>
      <div class="p-[20px] md:p-[30px] bg-[#13222F] border-2 border-[#5ABFA4] max-w-[823px]">
        <h1 class="text-lg md:text-xl text-white font-bold mb-[10px]">Extensive Network</h1>
        <p class="mb-[10px] text-white">
          With ARLOOPA’s success, we bring industry
          knowledge, networks, and reputation,
          which can aid in fundraising.
        </p>
      </div>
    </div>
</div>
<div class="bg-[#151A2F] px-[10px] py-[50px] md:py-[70px] lg:py-[88px]">
   <div class="relative">
     <img class="rounded-[30%] absolute top-0 left-[5%] md:left-[8%] w-[100px] md:w-[150px] lg:w-[200px]" src="/images/bg-1.png" alt="">
     <img class="rounded-[10%] absolute top-[80px] md:top-[110px] right-[5%] md:right-[10%] w-[120px] md:w-[180px] lg:w-[240px]" src="/images/bg-2.png" alt="">
   </div>
   <div class="flex flex-wrap justify-center items-center mb-[30px] md:mb-[41px] gap-[20px] md:gap-[30px] lg:gap-[50px]">
     <img src="/images/twitter.svg" alt="">
     <img src="/images/facebook.svg" alt="">
     <img src="/images/youtube.svg" alt="">
     <img src="/images/linked_in.svg" alt="">
     <img src="/images/upwork.svg" alt="">
   </div>
   <h1 class="text-white text-2xl md:text-3xl lg:text-4xl font-bold flex items-center justify-center mb-[16px] md:mb-[20px]">
     Don't miss out on the future of tech
   </h1>
   <p class="text-[#B9B9BF] text-sm md:text-base flex items-center justify-center px-[10px] md:px-[50px] lg:px-[100px]">
     Joining X-TECH means gaining early access to cutting-edge technology solutions and groundbreaking innovations.
   </p>
   <div class="flex flex-col md:flex-row items-center justify-center gap-[15px] md:gap-[20px] my-[30px] md:my-[50px]">
     <input type="text" placeholder="Enter Your Email Address"
            class="p-[10px] md:p-[15px] w-[200px] md:w-[300px] lg:w-[400px] border-2 border-[#5ABFA4] text-gray-700">
     <button class="group relative w-[120px] md:w-[140px] p-3 md:p-4 text-center uppercase font-black bg-transparent overflow-hidden transition-shadow duration-500">
       <span class="text-white relative z-10">CONTACT US</span>
       <span class="absolute inset-x-0 bottom-0 h-1 bg-transparent border-b-4 border-l-4 border-transparent transform translate-x-full transition-all duration-300 group-hover:border-[#16C2A3] group-hover:translate-x-0 group-hover:h-full"></span>
       <span class="absolute inset-x-0 top-0 h-1 bg-transparent border-t-4 border-r-4 border-transparent transform -translate-x-full transition-all duration-300 group-hover:border-[#16C2A3] group-hover:translate-x-0 group-hover:h-full delay-300"></span>
     </button>
   </div>
</div>
</template>
<script setup>
import FlickingComponent from "~/component/flickingComponent.vue";
import Asd from "~/component/asd.vue";
import CalendarComponent from "~/component/calendarComponent.vue";


const menu = ref(false)

function open() {
  if(menu.value === true){
    menu.value = false
  }else {
    menu.value = true
  }
}

</script>


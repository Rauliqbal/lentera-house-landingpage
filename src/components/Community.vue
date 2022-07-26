<template>
    
    <div class="relative">
        <div class="bg-slate-100 w-2/3 h-96 rounded-r-3xl"></div>

        <div class="container flex flex-col lg:flex-row items-center justify-center gap-8 px-5 lg:px-12 absolute top-[60px]">

        <div class="w-full lg:w-2/5">
            <h2 class="text-3xl lg:text-4xl font-semibold">Become a part <br> of our community</h2>
             <p class="text-gray-400 text-base lg:text-lg leading-loose mt-4">Grow and live together to pursue happiness that we always dreaming of</p>
        </div>

        <div class="w-[78%] lg:w-3/5">
            <swiper
                :slidesPerView="'auto'"
                :spaceBetween="30"
                :pagination="{
                clickable: true,
                }"
                :modules="modules"
                class="mySwiper">

                <swiper-slide class="w-[270px]">
                    <div class="relative">
                        <img class="w-52" src="../assets/images/user1.png" alt="user 1"> 
                        <div class="bg-[#EDEDFA] rounded-xl py-4 px-6 absolute top-[154px] right-0">
                            <h5 class="text-sm font-medium">Sabrina Kuku</h5>
                            <p class="text-[11px] text-gray-500 mt-1">My new family ever and <br>thanks to Lentera</p>
                        </div>
                    </div>
                </swiper-slide>

                <swiper-slide class="w-[270px]">
                    <div class="relative">
                        <img class="w-52" src="../assets/images/user2.png" alt="user 2"> 
                        <div class="bg-[#EDEDFA] rounded-xl py-4 px-6 absolute top-[154px] right-0">
                            <h5 class="text-sm font-medium">Sabrina Kuku</h5>
                            <p class="text-[11px] text-gray-500 mt-1">My new family ever and <br>thanks to Lentera</p>
                        </div>
                    </div>
                </swiper-slide>
                <swiper-slide class="w-[270px]">
                    <div class="relative">
                        <img class="w-52" src="../assets/images/user3.png" alt="user 3"> 
                        <div class="bg-[#EDEDFA] rounded-xl py-4 px-6 absolute top-[154px] right-0">
                            <h5 class="text-sm font-medium">Sabrina Kuku</h5>
                            <p class="text-[11px] text-gray-500 mt-1">My new family ever and <br>thanks to Lentera</p>
                        </div>
                    </div>
                </swiper-slide>
            </swiper>
        </div>
        
    </div>
    </div>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";


// import required modules
import { Pagination } from "swiper";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination],
    };
  },
};
</script>
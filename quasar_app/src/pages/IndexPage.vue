<template>
  <q-page class="flex flex-center tw-gap-12">
    <!-- <div class="tw-border tw-border-gray-800 tw-fixed tw-h-screen tw-z-10" :style="`left:${mouse.x}px`"></div>
    <div class="tw-border tw-border-gray-800 tw-fixed tw-h-screen tw-z-10" :style="`left:${mouse.x+330}px`"></div>
    <div class="tw-border tw-border-gray-800 tw-fixed tw-w-screen tw-z-10" :style="`top:${mouse.y}px`"></div>
    <div class="tw-border tw-border-gray-800 tw-fixed tw-w-screen tw-z-10" :style="`top:${mouse.y+280}px`"></div> -->
    <div class="tw-flex tw-flex-col tw-items-center">
      <img
        id="image"
        alt="refernce Doraemon"
        src="doraemon.png"
        class="tw-h-96 tw-border-2 tw-border-gray-700 tw-p-4 tw-border-dotted"
      >
      <span>Image</span>
    </div>

    <div class="tw-flex tw-flex-col tw-items-center">
      <div class="tw-p-4 tw-border-2 tw-border-gray-700">
        <div id="code" 
          class="tw-w-[245px] tw-h-[348px] tw-relative tw-flex tw-flex-col tw-items-center">
          <div class="tw-w-[212px] tw-h-[204px] tw-border-[1px] tw-border-black tw-bg-[#3891D5] tw-top-[2px] tw-absolute tw-rounded-[100px] skew-y-12">
            <!-- head bluepart -->
          </div>
          <div class="tw-w-[55px] tw-h-[67px]  tw-bg-white tw-border-[1px] tw-border-black tw-top-[10px] tw-left-[68px]
            tw-absolute tw-z-[2] " style="border-radius: 100px;">
            <div class="tw-h-2 tw-w-2 bg-black tw-rounded-full tw-absolute tw-bottom-3 tw-right-3"></div>
          </div>
          <div class="tw-w-[55px] tw-h-[67px] tw-bg-white tw-border-[1px] tw-border-black tw-top-[10px] tw-left-[121px]
            tw-absolute tw-z-[2] " style="border-radius: 100px;">
            <div class="tw-h-2 tw-w-2 bg-black tw-rounded-full tw-absolute tw-bottom-3 tw-left-3"></div>
          </div>
          <div class="tw-w-[23px] tw-h-[23px] tw-bg-[#E54926] tw-border-[1px] tw-border-black tw-top-[67px] tw-left-[110px]
            tw-absolute tw-z-[2] tw" style="border-radius: 100px;">
            <div class="tw-w-[8px] tw-h-[8px] tw-bg-white tw-rounded-full tw-top-[4px] tw-left-[5px]
            tw-absolute tw-z-[2]"></div>
          </div>
          <div class="tw-h-[58px] tw-w-[1px] tw-bg-black tw-absolute tw-z-[2] tw-top-[90px]"></div>
          <div class="tw-h-[1.4px] tw-w-[78px] tw-bg-black tw-absolute tw-z-[2] tw-top-[131px] tw-left-[47px] tw-rotate-[24deg]"></div>
          <div class="tw-h-[1.4px] tw-w-[78px] tw-bg-black tw-absolute tw-z-[2] tw-top-[131px] tw-left-[120px] tw-rotate-[-24deg]"></div>

          <div class="tw-h-[1px] tw-w-[37px] tw-bg-black tw-absolute tw-z-[2] tw-top-[85px] tw-left-[55px] tw-rotate-[10deg]"></div>
          <div class="tw-h-[1px] tw-w-[37px] tw-bg-black tw-absolute tw-z-[2] tw-top-[98px] tw-left-[55px] tw-rotate-[4deg]"></div>
          <div class="tw-h-[1px] tw-w-[37px] tw-bg-black tw-absolute tw-z-[2] tw-top-[112px] tw-left-[55px] tw-rotate-[0deg]"></div>

          <div class="tw-h-[1px] tw-w-[37px] tw-bg-black tw-absolute tw-z-[2] tw-top-[85px] tw-left-[156px] tw-rotate-[-10deg]"></div>
          <div class="tw-h-[1px] tw-w-[37px] tw-bg-black tw-absolute tw-z-[2] tw-top-[98px] tw-left-[156px] tw-rotate-[-4deg]"></div>
          <div class="tw-h-[1px] tw-w-[37px] tw-bg-black tw-absolute tw-z-[2] tw-top-[112px] tw-left-[156px] tw-rotate-[0deg]"></div>
          <div class="tw-w-[175px] tw-h-[160px] tw-border-[1px] tw-border-black tw-bg-white tw-top-[50px] tw-absolute tw-rounded-[100px] tw-z-[1]"></div>
          <div class="tw-w-[140px] tw-h-[9px] tw-bg-[#E54926] tw-top-[188px] tw-absolute tw-rounded-[3px] skew-y-12 tw-z-[1]
            tw-border-[1px] tw-border-black"></div>

          <div class="tw-bg-amber-300 tw-w-[27px] tw-h-[27px] tw-absolute tw-left-[107px] tw-top-[192px] tw-z-[3]
            tw-border-[1px] tw-border-x-[1px] tw-border-black " style="border-radius:50px 50px 50px 50px">
            <div class="tw-bg-black tw-w-[25px] tw-h-[2px] tw-absolute tw-left-[0px] tw-top-[10px] tw-z-[3]
            tw-border-[1px] tw-border-x-[1px] tw-border-black "></div>
            <div class="tw-bg-black tw-w-[25px] tw-h-[2px] tw-absolute tw-left-[0px] tw-top-[13px] tw-z-[3]
            tw-border-[1px] tw-border-x-[1px] tw-border-black "></div>
            <div class="tw-bg-black tw-w-[1px] tw-h-[6px] tw-absolute tw-left-[11.5px] tw-bottom-[0px] tw-z-[3]
            tw-border-[1px] tw-border-x-[1px] tw-border-black "></div>
            <div class="tw-bg-black tw-w-[6px] tw-h-[6px] tw-absolute tw-left-[9.5px] tw-bottom-[3px] tw-z-[3]
            tw-border-[1px] tw-border-x-[1px] tw-border-black tw-rounded-full "></div>
          </div>
          <div class="bg-white tw-w-full tw-h-[155px] bg-white tw-absolute tw-top-[197px] tw-z-[2] tw-overflow-hidden">
            <div class="tw-bg-[#3891D5] tw-w-[142px] tw-h-[95px] tw-absolute tw-left-[51px] tw-top-[26px] tw-z-[2]
              tw-border-b-[1px] tw-border-x-[1px] tw-border-black" style="border-radius:2px 2px 4px 4px">
              <div class="tw tw-w-[1.5px] tw-h-[11px] tw-absolute tw-left-[69px] tw-bottom-[0px] tw-bg-black"></div>
              <div class="tw tw-w-[11px] tw-h-[1.5px] tw-absolute tw-left-[64px] tw-bottom-[11px] tw-bg-black"></div>
            </div>
            <div class="tw-bg-white tw-w-[129px] tw-h-[115px] tw-absolute tw-left-[58px] tw-top-[-17px] tw-z-[2]
              tw-border-b-[1px] tw-border-x-[1px] tw-border-black tw-rounded-full">
              <div class="tw-bg-white tw-w-[92px] tw-h-[50px] tw-absolute tw-left-[17px] tw-top-[50px] tw-z-[2]
              tw-border-[1px] tw-border-x-[1px] tw-border-black " style="border-radius:0px 0px 50px 50px"></div>
            </div>
            <div class="tw tw-w-[71px] tw-h-[28px] tw-absolute tw-left-[51px] tw-top-[120px]
              tw-border-b-[1px] tw-border-r-[1px] tw-border-black" style="border-radius:2px 2px 5px 2px"></div>
            <div class="tw tw-w-[71px] tw-h-[28px] tw-absolute tw-left-[121px] tw-top-[120px]
              tw-border-b-[1px] tw-border-l-[1px] tw-border-black" style="border-radius:2px 2px 2px 5px"></div>
            <div class="tw tw-w-[71px] tw-h-[28px] tw-absolute tw-left-[34px] tw-top-[120px]
              tw-border-y-[1px] tw-border-l-[1px] tw-border-black" style="border-radius:40px 0px 0px 20px"></div>
            <div class="tw tw-w-[71px] tw-h-[28px] tw-absolute tw-left-[139px] tw-top-[120px]
              tw-border-y-[1px] tw-border-r-[1px] tw-border-black" style="border-radius:0px 40px 20px 0px"></div>
            <div class="tw-bg-[#3891D5] tw-w-[145px] tw-h-[30px] tw-absolute tw-left-[49px] tw-border-t tw-border-black tw-top-[-1px] tw-z-[1]" style="border-radius:2px 2px 0px 0px"></div>
            <div class="tw-bg-[#3891D5] tw-w-[65px] tw-rotate-[-50deg] tw-h-[30px] tw-left-[10px] tw-top-[16px] tw-absolute tw-border
              tw-border-black tw-z-[0]" style="border-radius:20px 5px 0px 20px"></div>
            <div class="tw-bg-[#3891D5] tw-w-[65px] tw-rotate-[50deg] tw-h-[30px] tw-left-[169px] tw-top-[16px] tw-absolute tw-border
              tw-border-black tw-z-[0]" style="border-radius:5px 20px 20px 0px"></div>
            <div class="tw-h-[38px] tw-w-[38px] bg-white bg-white tw-z-[2] tw-absolute tw-left-[1px] tw-top-[40px] tw-border tw-border-black tw-rounded-full"></div>
            <div class="tw-h-[38px] tw-w-[38px] bg-white bg-white tw-z-[2] tw-absolute tw-left-[205px] tw-top-[40px] tw-border tw-border-black tw-rounded-full"></div>
          </div>
        </div>
      </div>
      <span>My Code</span>
    </div>
    
  </q-page>
</template>

<script>
import { defineComponent,ref } from 'vue'

export default defineComponent({
  name: 'IndexPage',
  setup(){
    return{
      mouse:ref({})
    }
  },
  methods:{

  },
  mounted(){
    let self = this
    // console.log("mounted");
    // document.addEventListener('mousemove', function (e) {
    //   var _x = e.clientX || e.pageX;
    //   var _y = e.clientY || e.pageY;
    //   self.mouse = { x: _x, y: _y };
    // }, false)
    // setTimeout(()=>{
    //   let image = document.getElementById('image')
    //   let code = document.getElementById('code')
    //   console.log(image.clientHeight);
    //   console.log(image.clientWidth);
    //   console.log(code.style.height);
    //   console.log(code.style.width);
    //   code.style.height = image.clientHeight
    //   code.style.width = image.clientWidth
    // },500)
  },
  created(){
    // console.log("red");
  }
})
</script>

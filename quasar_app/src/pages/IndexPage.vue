<template>
  <q-page class="">
    <div class="tw-p-8">
      <q-card class=" tw-w-96 ">
        <q-card-section>
          <span class="tw-font-bold tw-text-xl">
            Doraemon
          </span>
          <q-btn @click="$router.push('/doraemon')" color="primary">Let's Go !</q-btn>
        </q-card-section>
      </q-card>
    </div>
    <!-- <span class="tw-text-gray-400 tw-text-lg">Will add something</span> -->
    
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

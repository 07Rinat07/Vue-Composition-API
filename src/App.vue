<script setup>
import { CheckCircleIcon } from '@heroicons/vue/24/solid'
import { ClockIcon, ListBulletIcon, ChartBarIcon } from '@heroicons/vue/24/outline'
</script>

<template>
  <header class="sticky top-0 z-20 flex items-center justify-between p-3 bg-white border-b">
    <a href="#">
      <img src="./assets/logo.png" alt="Logo" class="h-9" />
    </a>
    <a href="#" class="text-sm">
      <div v-if="false" class="flex items-center gap-1">
        Day complete!
        <CheckCircleIcon class="text-green-500 h-7" />
      </div>
      <div v-else class="flex items-center gap-1">
        <div>Progress: <span class="font-mono">20%</span></div>
        <div class="w-3 h-3 bg-red-500 rounded-full"></div>
      </div>
    </a>
  </header>

<main class="flex flex-col flex-grow">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Excepturi facilis cum nam ullam laboriosam tenetur obcaecati aperiam in nostrum voluptates exercitationem officia ipsa repudiandae quam, voluptatem maxime, mollitia fuga et qui sapiente accusantium id. Incidunt reprehenderit quisquam, asperiores laudantium impedit optio accusamus magnam iure voluptate facilis, rerum nam ducimus est quas porro! Dicta doloribus, repudiandae omnis ut molestias, molestiae cumque neque expedita unde debitis cupiditate ducimus sint perspiciatis repellendus ab recusandae dolores. Cum minima inventore, distinctio voluptas explicabo illum reprehenderit voluptatem! Odit repudiandae cumque nemo nostrum nam maxime assumenda sed et esse cupiditate autem at corporis doloribus consequuntur non animi, omnis in laborum ipsam aut sapiente vero? Officiis maiores iste, tenetur, in recusandae omnis magnam repudiandae unde est aut asperiores dignissimos. Pariatur optio aliquam dolores, fugit repellat similique officiis placeat, voluptate eos, eveniet iure inventore ullam ducimus debitis non accusamus dolorem perferendis tenetur consectetur error suscipit. Dolorum culpa quod amet expedita adipisci, quasi asperiores quae exercitationem tenetur corporis inventore, ut doloremque a ad dignissimos cum deserunt quos nobis nostrum ratione sunt. Rem accusantium dolorum corrupti perspiciatis atque ex corporis necessitatibus fugiat asperiores. Harum quaerat enim fuga sit unde explicabo sapiente deserunt rem repellat nemo hic error reprehenderit iste, autem eos repudiandae iure distinctio inventore natus! Quaerat tempora perspiciatis voluptatum ex unde excepturi esse, iusto labore quo officiis. Ut reprehenderit, non harum cum architecto sed voluptates corrupti id vitae ea libero suscipit rem odit excepturi tenetur similique eius quibusdam, repellat possimus neque dolore nemo consectetur! Placeat consectetur voluptates omnis illo assumenda temporibus sequi recusandae, labore aperiam non corrupti, cum laboriosam? Cum facere accusantium magnam deleniti ullam laborum blanditiis dicta nemo corporis veritatis, rerum, in dolore aliquid culpa dolores tempora? Voluptas dolorum pariatur quidem quod, eius fugit recusandae beatae praesentium nulla, accusantium vero reiciendis magnam, sapiente accusamus molestias nostrum ipsum laboriosam quia.</main>

<nav class="sticky bottom-0 z-10 bg-white">
  <ul class="bottom-0 flex items-center justify-around border-t">
    <li class="flex-1">
      <a class="flex flex-col items-center p-2 capitalize test-xs" href="#timeline">
       <ClockIcon class="w-6 h-6" /> timeline
      </a>
    </li>
    <li class="flex-1">
      <a class="flex flex-col items-center p-2 capitalize test-xs" href="#activities">
        <ListBulletIcon class="w-6 h-6" /> activities
      </a>
    </li>
    <li class="flex-1">
      <a class="flex flex-col items-center p-2 capitalize test-xs" href="#progress">
        <ChartBarIcon class="w-6 h-6" /> progress
      </a>
    </li>
  </ul>
</nav>
  
</template>

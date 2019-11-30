 <template>
 <div>
    <div v-for="o in 4" :key="o" class="text item">
      <a href="https://www.ele.me" target="_blank">{{'List item ' + o }}</a>
      <el-divider></el-divider>
    </div>
  </div>
</template>
<style>
.NuxtLogo {
  animation: 1s appear;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>

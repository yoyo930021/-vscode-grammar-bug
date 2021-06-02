<template>
  <div :id="arg" v-if="typeof blah !== 'undefined'">
    <p :test="typeof junk === 'string'" :class="stuff && 'moreStuff'" 
    @click="doAThing()">
      {{ junk }}
    </p>
    <div id="">

    </div>
    <div>

    </div>
  </div>
</template>

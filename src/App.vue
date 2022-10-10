<!--
 * @Author: yanghui yanghui0711@rayootech.com
 * @Date: 2022-10-10 10:47:46
 * @LastEditors: yanghui yanghui0711@rayootech.com
 * @LastEditTime: 2022-10-10 15:17:02
 * @FilePath: \1\src\App.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

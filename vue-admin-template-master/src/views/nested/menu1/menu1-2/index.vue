<template>
  <div class="chart-container">
    <chart height="100%" width="100%" />
    <el-alert :closable="false" title="menu 1-2" type="success">
      <router-view />
    </el-alert>

  </div>
</template>



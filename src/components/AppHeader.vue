<template>
  <div class="title">
    <img :src="image" /> 
    <a-page-header style="padding: 0.5em; 
    font-size: xx-large;
    font-weight: 100; 
    display: flex; 
    justify-content: center;
    margin-top: 0em;
    margin-bottom: 0.5em;">Area Explorer Dashboard</a-page-header>
  </div>
  <a-menu mode="horizontal" style="justify-content: center;">
    <a-menu-item>
      <template #icon>
        <dashboard-outlined />
      </template>
      Live Detection
    </a-menu-item>
    <a-menu-item>
      <template #icon>
        <line-chart-outlined />
      </template>
      Path Optimization
    </a-menu-item>
    <a-menu-item>
      <template #icon>
        <menu-outlined />
      </template>
      Settings
    </a-menu-item>
  </a-menu>
</template>

<script setup>
  import { LineChartOutlined, DashboardOutlined, MenuOutlined } from '@ant-design/icons-vue';
  import image from "./images/icons8-hard-to-find-50.png"
</script>




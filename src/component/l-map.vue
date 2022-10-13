 
<script>
export default {
    name: 'l-map',
}
</script>
<script  setup>
import * as Cesium from "cesium";
import "cesium/Build/Cesium/Widgets/widgets.css";
import { onMounted } from "vue";

onMounted(() => {
    const viewer = new Cesium.Viewer("cesiumContainer");

});




</script>
<template>

    <div id="cesiumContainer"></div>

<slot></slot>
</template>
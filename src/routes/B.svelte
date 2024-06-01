<script lang="ts">
import { T } from '@threlte/core'
import { GLTF, OrbitControls } from '@threlte/extras'
</script>


<T.PerspectiveCamera
makeDefault

position={[10, 10, 10]}
fov={25}
axis={{}}
view={{
    enabled:true,
    fullWidth: 20,
    fullHeight: 20,
    offsetX:6,
    offsetY:-8,
    width: 20,
    height: 20,
}}
zoom={0.5}
>
<OrbitControls
    enableDamping
/>

</T.PerspectiveCamera>

<T.AmbientLight />

<GLTF url="/result.gltf" />
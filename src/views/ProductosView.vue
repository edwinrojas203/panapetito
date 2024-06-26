<script setup>
import { useRoute } from "vue-router"
import productos from "@/components/productos.vue"

const ruta = useRoute()
const categoria = ruta.params.categoria;

</script>

<script lang="ts"
>
const currentTime = new Date()
const currentHorus = currentTime.getDate()
let saludo = ""

if(currentHorus < 12){
    saludo = "Buenos Dias"
}
else if(currentHorus > 12 && currentHorus < 9){
    saludo="Buenas Tardes"
}else saludo = "Buenas noches"
</script>

<h1 class="text-3xl font-bold text-white">{saludo}</h1>
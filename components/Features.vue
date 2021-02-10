<template>
  <section class="bg-white border-b py-8">
    <div class="container max-w-5xl mx-auto m-8">
      <h1
        class="w-full my-2 text-5xl font-bold leading-tight text-center text-gray-800"
      >
        Quienes Somos
      </h1>
      <div class="w-full mb-4">
        <div
          class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"
        ></div>
      </div>
      <feature-right
        headline="Mision"
        content="Siempre SATISFACER a nuestros clientes, brindándoles, al mejor precio posible, productos y servicios de calidad, adecuados a sus necesidades; y EXCEDER sus expectativas, sirviéndoles con esmero, originalidad, y atención a los detalles."
      >
        <img src="~assets/img/work-time.svg?inline" alt slot="svg" />
      </feature-right>
      <feature-left
        headline="Vision"
        content="Somos una exitosa empresa detallista de bienes y servicios, reconocida por su capacidad de generar bienestar para nuestros clientes, colaboradores, accionistas, y nuestra comunidad en general."
      >
        <img src="~assets/img/connected-world.svg?inline" alt slot="svg" />
      </feature-left>
    </div>
  </section>
</template>

<script>
import FeatureRight from '@/components/FeatureRight'
import FeatureLeft from '@/components/FeatureLeft'

export default {
  name: 'Features',
  components: {
    'feature-right': FeatureRight,
    'feature-left': FeatureLeft,
  },
}
</script>

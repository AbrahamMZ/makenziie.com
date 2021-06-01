<template>
  <section class="bg-white border-b py-8">
    <feature-right
      headline="A partir del 01 de Julio 2021 celebraremos una fusión estratégica y comercial con G Intregral Bajio "
      content="Comprometiéndonos en brindarles una gran calidad y satisfacción de servicio además de una amplia gama de oportunidades para tu negocio."
    >
      <img src="~/assets/img/logo_gintegral.png?inline" width="300" alt slot="svg" />
    </feature-right>
  </section>
</template>

<script>
import FeatureRight from "@/components/FeatureRight";
export default {
  name: "Banner",
  components: {
    "feature-right": FeatureRight,
  },
};
</script>

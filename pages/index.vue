<template>
  <div>
    <hero />
    <banner />
    <features />
    <!-- <teasers /> -->
    <call-to-action />
  </div>
</template>

<script>
import Hero from "@/components/Hero";
import Features from "@/components/Features";
import Banner from "@/components/Banner";
import Teasers from "@/components/Teasers";
import CallToAction from "@/components/CallToAction";
import logo from "~/assets/img/logo_gintegral.png";

export default {
  name: "LandingPage",
  components: {
    hero: Hero,
    features: Features,
    teasers: Teasers,
    banner: Banner,
    "call-to-action": CallToAction,
  },
  mounted() {
    this.$swal({
      title: "A todos nuestro clientes y proveedores",
      html:
        "Les agradecemos por contar siempre con su preferencia y confianza, no nos despedimos si no todo lo contrario, les anunciamos una gran fusión que nos incorporaremos con <br><b>G Integral Bajío</b> a partir del 01 de junio de 2021, con el objetivo de brindarles como siempre el mejor servicio y profesionalismo.<br> ¡ Gracias totales !",
      imageUrl: logo,
      imageWidth: 200,
      imageHeight: 200,
      imageAlt: "makenzie_alt",
      width: 600,
    });
  },
};
</script>

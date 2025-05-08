<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    p.mb-5 El siguiente mapa integra los criterios y especificidades de los conocimientos expuestos en el presente componente formativo.
    
    .row.justify-content-center
      .col-lg-12.mb-5
        .row.justify-content-center
          .col-lg-9
            figure
              img(src="@/assets/curso/temas/sintesis.svg", alt="En la síntesis del procedimiento para la fabricación de panela se realiza de la siguiente manera. 1. Recepción de materia prima (caña de azúcar), se hace una inspección del material vegetativo. 2. Luego pasamos a la molienda, se debe hacer el proceso de prensado con el trapiche eléctrico (proceso de transformación). 3. Selección de sustancias azucaradas (jugo): se procede con el proceso de retirado de cachaza (proceso de separación) y colado manual. Este proceso se demora 10 minutos. 4. Luego sigue la cocción del jugo, este proceso tiene un tiempo de duración de 20 minutos, se debe realizar la inspección del punto óptimo (ingreso-proceso). 5. Se sigue con el proceso de enfriamiento, este proceso tiene un tiempo de 180 minutos, se sigue con el retirado del fuego. 6. Luego se debe dejar en reposo de 3 horas con el proceso de manipulación de la miel o melcocha, se hace la inspección de manipulación. 7. Luego se pasa con moldear la miel o melcocha, esto se hace con la utilización de cesta. 8. Luego se sigue con la obtención de la panea criolla, se hace el retirado de cesta. 9. Se sigue con el proceso de empacado, este se hace con envoltura con hoja de bijao. 10. Luego se pasa a bodega para su respectivo almacenamiento. 11. Seguiríamos con el proceso de transporte y por último 12. Ventas, este proceso se divide en tres procesos, los minoristas (tiendas), los mayoristas y los detallistas (usuarios).")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>

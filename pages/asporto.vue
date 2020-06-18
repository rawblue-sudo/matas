<template>
  <div id="asporto" class="Storia">
    <div class="placeholder mobile">
      <img class="pizza" src="pizzaiolo.gif" />
    </div>

    <div class="Asporto">
      <h1>Servizio da asporto</h1>

      <img class="servizio" src="../static/svg/distance.svg" alt="Pickup" />
      <p>
        Prenotazione via telefono. <br />Vi sarà dato un orario di ritiro
        <br class="mobile" />per garantire la distanza sociale
      </p>

      <!-- <h2>Consegna in centro storico</h2>
          <a href="https://www.google.it/maps/place/Via+Nicola+Matas,+54,+60121+Ancona+AN,+Italia/@43.6211713,13.5093447,17z/data=!3m1!4b1!4m5!3m4!1s0x132d7fbb060b2c07:0x3aaec169bd563617!8m2!3d43.6211674!4d13.5115334" target="_blank">
            <img class="mappa" src="Consegna.jpg" alt="Consegna nel raggio del Centro storico">
          </a> -->

      <img class="servizio" src="../static/svg/apertura.svg" alt="Apertura" />
      <p>
        Apertura da martedì a domenica <br />Prenotazioni dalle 16:00 in poi
        <br />
        Consegne dalle 19:00 alle 21:30
      </p>
      <img class="servizio" src="../static/svg/phone.svg" alt="Telefono" />
      <p>Prenotazione <a href="tel:0719943040"> 0719943040</a></p>
      <!-- <img class="servizio" src="../static/svg/pizza.svg" alt="Pizza in consegna">
           <p>Gratis per ordine superiore a 25€, altrimenti a 2€</p> -->
      <img class="servizio" src="../static/svg/payment.svg" alt="Pagamento" />
      <p>Vengono accettate carte di credito e contanti</p>
      <img class="servizio" src="../static/svg/menu.svg" alt="Menu" />
      <p>
        Il menù da asporto si trova cliccando
        <a href="MENU DA ASPORTO.pdf" style="text-decoration: underline;"
          >qui</a
        >
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Asporto'
}
</script>

<style></style>

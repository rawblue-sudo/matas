<template>
  <div id="locale" class="Storia">
    <div class="Descrizione padded">
      <h1>
        Matas 54 Ancona <span class="mobile">-</span>
        <br class="desktop" />Pizza & Tagliere
      </h1>
      <picture>
        <source media="(min-width: 1024px)" srcset="/bancone.jpg" />
        <source srcset="/bancone-mobile.jpg" />
        <img class="locale" src="bancone.jpg" alt="Matas 54 Bancone" />
      </picture>

      <p>
        <strong>Stefano Morini e Antonio De Iure</strong>, sull’onda del
        rilancio del Quartiere Guasco di Ancona, insieme nel progetto
        <strong><em>MATAS54</em></strong
        >, fanno rivivere un locale storico che nel tempo ha avuto destinazioni
        diverse, dall’antica <em>Ciancianella</em>, ritrovo dei giovani
        anconetani degli anni ’70, alla <em>Pizzeria Jasmine</em>.
      </p>

      <p>
        Un luogo storico ha migliaia di anime che lo hanno attraversato nei
        secoli. E un locale affascinante come quello di Via Matas 54 aveva solo
        bisogno di far emergere l’anima che più si addiceva al pensiero dei
        nuovi gestori.
      </p>
      <picture>
        <source media="(min-width: 1024px)" srcset="/forno.jpg" />
        <source srcset="/forno-mobile.jpg" />
        <img class="locale" src="forno.jpg" alt="Matas 54 Forno" />
      </picture>

      <p>
        Grazie alla collaborazione con lo studio di Architettura Sardellini
        Marasca e all’impegno e competenza del suo team, <em>MATAS54</em>, senza
        snaturare lo stile e l’atmosfera dell’antico palazzo di cui fa parte, ha
        assunto, attraverso i colori, i materiali e le luci, l’aspetto di un
        locale nuovo e contemporaneo.
      </p>

      <p>
        Un luogo giovane e informale, facile ma non banale, dove sentirsi a
        proprio agio, un luogo anche internazionale, un pò <em>hipster</em> e
        pronto ad accogliere chiunque.
      </p>

      <p>
        Dalla primavera all’autunno <em>MATAS54</em> si apre sulla piazza San
        Francesco, ai piedi del maestoso portale della Chiesa che la sovrasta,
        in un ambiente raccolto di unica bellezza.
      </p>

      <p>
        <center>
          <span id="mostra" onclick="collapse()">Mostra di più</span>
        </center>
      </p>
      <script>
        function collapse() {
          let x = document.getElementById('piu')
          let y = document.getElementById('mostra')
          if (x.style.display === 'none') {
            x.style.display = 'block'
            y.innerHTML = 'Mostra di meno'
          } else {
            x.style.display = 'none'
            y.innerHTML = 'Mostra di più'
          }
        }
      </script>

      <div id="piu" class="Descrizione">
        <h2>Più della pizzeria Matas 54</h2>

        <p>
          Il filo conduttore del progetto è stato di far emergere quest’anima
          tentando di generare e comunicare una nuova esperienza urbana e
          gastronomica che fosse in grado di coop-tare l’avventore dalla strada
          e trasportarlo in un nuovo mondo.
        </p>
        <p>
          L’immagine è rinnovata già sulla via dove da una grande porta bilico
          trasparente si in-travede la nuova distribuzione interna e la grande
          scritta a tubo neon sul fondo della pri-ma sala.
        </p>
        <picture class="locale">
          <source srcset="/locale.webp" type="image/webp" />
          <source srcset="/locale.png" type="image/png" />
          <img class="locale" src="/locale.png" alt="Matas 54 Locale" />
        </picture>

        <p>
          La prima sfida di questo progetto è stata proprio di appropriarsi e
          caratterizzare la prima sala che, da sempre, è stata solo luogo di
          passaggio, mentre oggi diventa il cuore pulsante del locale.
        </p>
        <p>
          Una nuova parete in ferro grezzo la taglia in diagonale, scandisce lo
          spazio dedicato alla cucina, nascondendone alcune parti più di
          servizio e scoprendo quella più significativa, ovvero il mondo del
          pizzaiolo e del nuovo forno Moretti Neapolis dal design innovativo.
        </p>
        <picture class="locale mobile">
          <source srcset="/entrata.webp" type="image/webp" />
          <source srcset="/entrata.jpg" type="image/jpg" />
          <img class="locale mobile" src="/entrata.jpg" alt="Matas 54 Locale" />
        </picture>
        <p>
          Sul fronte speculare c’è il grande spazio dell’accoglienza e della
          convivialità: un grande bancone/scultura in ferro grezzo è l’elemento
          centrale del servizio al banco, un’affettatrice Berkel é sovrastata da
          una collezione di antichi taglieri appesi al muro; la grande parete
          rosso scuro del retrobanco é arricchita da una composizione in cotto
          arti-gianale smaltato sempre sui toni caldi dei rossi.
        </p>
        <picture class="locale desktop">
          <source srcset="/banco.webp" type="image/webp" />
          <source srcset="/banco.jpg" type="image/jpg" />
          <img class="locale desktop" src="/banco.jpg" alt="Matas 54 Locale" />
        </picture>
        <p>
          Il banco e il mensolone in ferro dell’ingresso sottolineano la volontà
          di creare un ambien-te intimo, informale, dove appoggiarsi, prendere
          un aperitivo al volo o un tagliere, magari mentre si aspetta una
          pizza. Ma la vera sorpresa è la sala storica dalle volte a crociera in
          mattoni, un tesoro nascosto che solo salendo i tre gradini che
          separano le due sale sarà possibile scoprire. Le bellissime volte
          custodite gelosamente nel tempo, sono arricchite da un nuovo spirito
          di libertà che aleggia e caratterizza tutto il nuovo locale: un gioco
          di luci creato con lampade a cono nere opache che fluttuano nello
          spazio e i cavi tesi che sfiorano le volte e tracciano percorsi visivi
          ai quali si ricollega la grafica murale dell’identità visuale creata
          appositamente dall’artista francese Hélène Valverde.
        </p>
        <picture class="locale desktop">
          <source srcset="/sala.webp" type="image/webp" />
          <source srcset="/sala.jpg" type="image/jpg" />
          <img class="locale desktop" src="/sala.jpg" alt="Matas 54 Locale" />
        </picture>
        <p>
          Per finire, un bellissimo pavimento stonalizzato in microcemento
          grigio caldo lega tutti gli ambienti unificandone l’immagine generale.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {},
  head() {
    return {
      title: 'Matas 54 - Pizza & Tagliere',
      meta: [{ hid: 'yo', name: 'app', content: 'about matas' }]
    }
  }
}
</script>

<template>
<div class="about pa-10">
  <h1 style="color: crimson">Achievements</h1><br>
  <v-data-table
    :headers="headers"
    :items="headers2"
    :items-per-page="4"
    class="elevation-2"
  ></v-data-table>
</div>
</template>

<script>
  export default {
    data () {
      return {
        headers: [
          {
            text: 'Achievements',
            align: 'start',
            sortable: false,
            value: 'name',
          },
          { text: 'Books', value: 'books' },
          { text: 'Discoveries', value: 'discovery' },
        ],
        headers2: [
          {
            name: 'Adams Prize (1966)',
            books: "A BRIEF HISTORY OF TIME",
            discovery: "HAWKING CO-DISCOVERED THE FOUR LAWS OF BLACK HOLE MECHANICS"
          },
          {
            name: 'Eddington Medal (1975)',
            books: "The Theory of everything",
            discovery: "HIS MOST SIGNIFICANT THEORY IS THAT BLACK HOLES EMIT THE HAWKING RADIATION"
          },
          {
            name: 'Albert Einstein Award (1978)',
            books: "Black Holes and Baby Universes",
            discovery: "HE CONTRIBUTED TO THE THEORY OF COSMIC INFLATION"
          },
          {
            name: 'RAS Gold Medal (1985)',
            books: "The Universe in a Nutshell",
            discovery: "ALONG WITH ROGER PENROSE, HE DID GROUND-BREAKING WORK ON SINGULARITIES"
          }
        ],
      }
    },
  }
</script>
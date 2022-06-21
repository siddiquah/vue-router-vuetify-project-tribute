<template>
  <div class="about pa-10">
    <h1 style="color: crimson">About </h1><br>
    <p>Stephen Hawking was regarded as one of the most brilliant theoretical physicists in history. His work on the origins and structure of the universe, from the Big Bang to black holes, revolutionized the field, while his best-selling books have appealed to readers who may not have Hawking's scientific background. Hawking died on March 14, 2018, at the age of 76.</p>
    <p>Stephen Hawking was seen by many as the world's smartest person, though he never revealed his IQ score. <br><br>Over the course of his career, Hawking studied the basic laws governing the universe. He proposed that, since the universe boasts a beginning — the Big Bang — it likely will have an ending. Working with fellow cosmologist Roger Penrose, he demonstrated that Albert Einstein's Theory of General Relativity suggests that space and time began at the birth of the universe and ends within black holes, which implies that Einstein's theory and quantum theory must be united. 
      Using the two theories together, Hawking also determined that black holes are not totally dark but instead emit radiation. He predicted that, following the Big Bang, black holes as tiny as protons were created, governed by both general relativity and quantum mechanics. </p><br>
    <em style="color: #ccc ">Remember to look up at the stars ~ Stephen Halking</em><br><br>
    <ul>
        <li><b>1942-</b> Born January 8, in Oxford, England. This was the 300th anniversary the death of Galileo.</li>
        <li><b>1958-</b> With help from his mathematics teacher Stephen built a computer from anything they could find.</li>
        <li><b>1959-</b> At the age of 17 Stephen was awarded a scholorship to the University of Oxford</li>
        <li><b>1962-</b> Graduated with Honors in Natural Science from Oxford and began graduate work at Trinity Hall, Cambridge.</li>
        <li><b>1964-</b> Stephen publicly challenged the work of noted astronomer Fred Hoyle</li>
        <li><b>1966-</b> Obtained his PhD in Applied Mathematics and Theoretical Physics</li>
        <li><b>1968-</b> A joint essay co-written with Roger Penrose was the runner-up at the Gravity Research Foundation competition.</li>
        <li><b>1970-</b> Appointed to the Sherman Fairchild Distinguished visiting professorship at the California Institute of Technology (Caltech).</li>
        <li><b>1971-</b> Stephens essay titled "Black Holes" won the Gravity research Foundation Award.</li> 
        <li><b>1973-</b> He began to study Quantum Gravity and Quantum Mechanics.</li>
        <li><b>1974-</b> Elected a Fellow of the Royal Society.</li>
        <li><b>1975-</b> Awarded the Eddington Medal</li>
        <li><b>1979-</b> Awarded the Albert Einstein Medal.</li>
        <li><b>1982-</b> Began writing "A Brief History of Time".</li>
        <li><b>1985-</b> Lost his ability to speak after a tracheotomy was performed to save his life when he came ill with pneumonia.</li>
        <li><b>1986-</b> Received a computer program called the "Equalizer" from Walter Wotosz, CEO of Words Plus. The Equalizer ran on an Apple II computer linked to a speech synthesizer. He could communicate approximately 15 words per minute using a hand clicker.</li>
        <li><b>1988-</b> "A Brief History of Time" was published.</li>
        <li><b>1989-</b> Received the Princec of Asturias Wards in Concord and made a Companion of Honour.</li>
        <li><b>1993</b>- Recorded his synthesied voice for the song <i>Keep Talking</i> by <i>Pink Floyd</i></li>
        <li><b>1998-</b> "A Brief History of Time" was recorded in the Guinness Book of Records for being on The Sunday Times best-sellers list for 237 weeks.</li>
        <li><b>1999-</b> Appeared on the <i>The Simpsons</i>.</li>
        <li><b>2001-</b> Appeared on the documentary series <i>The Real Stephen Hawking</i></li>
        <li><b>2002-</b> Published "On The Shoulders of Giants".</li>
        <li><b>2003-</b> Called the Invasion of Iraq a War Crime.</li>
        <li><b>2005-</b> "Information Loss in Black Holes" and "Black Holes and the Information Paradox" were published.</li>
        <li><b>2006-</b> He posted an open question on the internet <i>"In a world that is in chaos poitically, socially and environmentally, how can the human race sustain another 100 years?"</i></li>
        <li><b>2007-</b> Courtesy of Zero Gravity Corporation Stephen participated in a zero-gravity flight.</li>
        <li><b>2009-</b> June of this year Stephen held a party but didn't advertise it until it was over, obviously nobody showed up. This was his way of proving time-travelling to the past was not possible.</li>
        <li><b>2011-</b> Narrating for the television series Curiosity on the Discovery Hawking stated: <br> <em>"We are each free to believe what we want and it is my view that the simplest explanation is there is no God. No one created the universe and no one directs our fate. This leads me to a profound realization. there is probably no heaven, adn no afterlife either. We have this one life to appreciate the grand design of the universe, and for that I am extremely grateful".</em></li>
        <li><b>2012-</b> Conceeded he was wrong for saying the Higgs boson particle would never be found. </li>
        <li><b>2012-</b> Appeared on the <i>Big Bang Theory</i></li>
        <li><b>2013-</b> Expressed support ofr the legalisation of assisted suicide for terminally ill.</li>
        <li><b>2014-</b> Announced he is an atheist.</li>
        <li><b>2015-</b> Helped launch Breakthrough Initiatives, a program to search for extraterrestrial intelligence.</li>
      </ul>  <br>  <br>
      
  <div class="text-center">
    <v-dialog
      v-model="dialog"
      width="500"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="red lighten-2"
          dark
          v-bind="attrs"
          v-on="on"
        >
          Read more!
        </v-btn>
      </template>

      <v-card>
        <v-card-title class="text-h5 grey lighten-2">
          Read more
        </v-card-title>

        <v-card-text>
          <br>To learn more about one of the greatest minds of the human civilization - Stephen Halking, visit https://en.wikipedia.org/wiki/Stephen_Hawking
        </v-card-text>

        <v-divider></v-divider>

        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn
            color="primary"
            text
            @click="dialog = false"
          >
            close
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>
  </div>
  </div>

  

</template>
<!-- 
<style scoped>
  div {
    background-color: #1B1C1D;
  }
</style> -->

<script>
  export default {
    data () {
      return {
        dialog: false,
      }
    },
  }
</script>

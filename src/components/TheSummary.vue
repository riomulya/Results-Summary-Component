<template>
  <div class="summary">
    <p class="title-summary">Summary</p>
    <div class="summary-container">
      <div>
        <div class="reaction">
          <div class="desc">
            <img
              src="../assets/images/icon-reaction.svg"
              alt="reaction"
            />Reaction
          </div>
          <div class="all-score">
            <span class="score">80</span>
            <span class="final-score"> / 100</span>
          </div>
        </div>
        <div class="memory">
          <div class="desc">
            <img src="../assets/images/icon-memory.svg" alt="memory" />Memory
          </div>
          <div class="all-score">
            <span class="score">92</span>
            <span class="final-score"> / 100</span>
          </div>
        </div>
        <div class="verbal">
          <div class="desc">
            <img src="../assets/images/icon-verbal.svg" alt="verbal" />Verbal
          </div>
          <div class="all-score">
            <span class="score">61</span>
            <span class="final-score"> / 100</span>
          </div>
        </div>
        <div class="visual">
          <div class="desc">
            <img src="../assets/images/icon-visual.svg" alt="visual" />Visual
          </div>
          <div class="all-score">
            <span class="score">72</span>
            <span class="final-score"> / 100</span>
          </div>
        </div>
      </div>
      <div class="btn-continue">Continue</div>
    </div>
  </div>
</template>

<style scoped>
.btn-continue {
  display: flex;
  justify-content: space-evenly;
  background-image: linear-gradient(#7857ff, #2e2be9);
  border-radius: 25px 25px;
  width: 15rem;
  height: 2rem;
  margin: 1rem auto;
  color: white;
  padding: 0.7rem 0 0 0;
  cursor: pointer;
}

.btn-continue:hover {
  background-image: linear-gradient(#704ff3, #403de6);
}

.title-summary {
  font-weight: bold;
  color: hsl(224, 30%, 27%);
  margin: 2rem 0 0.5rem 1rem;
}

.summary-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 1rem;
  margin: auto;
}

img {
  margin-right: 0.6rem;
}
.reaction {
  display: flex;
  justify-content: space-between;
  padding: 0.5rem;
  margin-bottom: 0.5rem;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
  background-color: hsla(0, 100%, 67%, 0.2);
  border-radius: 0.5rem;
  color: hsl(0, 100%, 67%);
}

.memory {
  display: flex;
  justify-content: space-between;
  padding: 0.5rem;
  margin-bottom: 0.5rem;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
  background-color: hsla(39, 100%, 56%, 0.2);
  border-radius: 0.5rem;
  color: hsl(39, 100%, 56%);
}
.verbal {
  display: flex;
  justify-content: space-between;
  padding: 0.5rem;
  margin-bottom: 0.5rem;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
  background-color: hsla(166, 100%, 37%, 0.2);
  border-radius: 0.5rem;
  color: hsl(166, 100%, 37%);
}
.visual {
  display: flex;
  justify-content: space-between;
  padding: 0.5rem;
  margin-bottom: 0.5rem;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
  background-color: hsla(234, 85%, 45%, 0.2);
  border-radius: 0.5rem;
  color: hsl(234, 85%, 45%);
}

.score {
  color: hsla(224, 30%, 27%, 1);
  margin: 0 0.3rem 0 1rem;
  display: flex;
  justify-self: end;
}

.all-score {
  display: flex;
  font-weight: bold;
  color: hsla(224, 30%, 27%, 0.5);
}
.final-score {
  display: flex;
  justify-self: end;
}

.desc {
  display: flex;
}
</style>

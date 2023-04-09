<template>
  <div class="result">
    <p class="title-result">Your Result</p>
    <div class="circle-result">
      <span class="all-score">
        <div class="score-result">76</div>
        <div class="end-score">of 100</div>
      </span>
    </div>
    <div class="grade">Great</div>
    <div class="description">
      You scored higher than 65% of the people who have taken these tests.
    </div>
  </div>
</template>

<style scoped>
.result {
  text-align: center;
  background-image: linear-gradient(#7857ff, #2e2be9);
  border-radius: 25px 25px;
  color: white;
}

.btn-continue {
  background-image: linear-gradient(#7857ff, #2e2be9);
  border-radius: 25px 25px;
  width: 5rem;
  height: 1rem;
  padding: 5px;
  margin: auto;
  color: white;
}

.score-result {
  font-size: 70px;
  font-weight: bold;
  font-family: 'Hanken Grotesk', sans-serif;
  margin-top: 1rem;
}

.circle-result {
  height: 10rem;
  width: 10rem;
  border-radius: 50%;
  background-color: hsla(241, 72%, 46%, 0.3);
  margin: auto;
  margin-top: 1rem;
  margin-bottom: 1rem;
}

.all-score {
  margin: 1rem;
}

.end-score {
  font-family: 'Hanken Grotesk', sans-serif;
  opacity: 0.3;
}

.title-result {
  opacity: 0.8;
  font-size: medium;
  font-family: 'Hanken Grotesk', sans-serif;
  margin-top: 2rem;
}

.grade {
  font-weight: bold;
  font-size: 1.5rem;
  margin: 10px;
}

.description {
  opacity: 0.7;
  font-size: smaller;
  font-weight: lighter;
  padding: 0 3rem;
}

@media (min-width: 320px) and (max-width: 767px) {
  .result {
    border-radius: 0 0 25px 25px;
  }
  .description {
    margin-bottom: 1rem;
    opacity: 0.9;
    font-weight: normal;
  }
}
</style>

<template>
  <Layout>
    <div class="container">

      <div class="competitor-header">
        <p>
          Analysis of competitor products.
          Sports watch products and traditional cardio workout products have been excluded as not being a competitor as such
        </p>
      </div>
      <table style="width:100%">
        <thead>
          <tr>
            <td>
              Competitor
            </td>
            <td>
              Link
            </td>
            <td>
              Key USP
            </td>
            <td>
              Audience
            </td>
            <td>
              Comments
            </td>
        </tr>
        </thead>
        <tbody>
          
          <tr>
            <td>MyPhysio Rehab</td>
            <td><a href="https://www.myphysiorehab.com/">Link</a></td>
            <td>Large existing library of rehab exercises</td>
            <td>Physio clients</td>
            <td>Comments</td>
        </tr>
          <tr>
            <td>Rehab guru</td>
            <td><a href="https://www.rehabguru.com/">Link</a></td>
            <td>Telehealth - video calls</td>
            <td>Physio clients</td>
            <td>Rehab guru is the strongest competitor - a decent exercise library, and the telehealth feature make it a strong contender</td>
        </tr>
          <tr>
            <td>Rehab My Patient</td>
            <td><a href="https://www.rehabmypatient.com/">Link</a></td>
            <td></td>
            <td>Physio clients</td>
            <td>A not quite as good version of rehab guru</td>
        </tr>
          <tr>
            <td>Physiotec</td>
            <td><a href="https://physiotec.ca/ca/en/">Link</a></td>
            <td>Similar to rehab guru/rehab my patient - but integrates directly with practice management software</td>
            <td>Physio clients</td>
            <td>Comments</td>
        </tr>
          <tr>
            <td>SimpleSet Pro</td>
            <td><a href="https://www.simpleset.net/">Link</a></td>
            <td>Physio clients</td>
            <td>More clinically oriented than the apps mentioned above</td>
            <td>Comments</td>
        </tr>
          <tr>
            <td>True Coach</td>
            <td><a href="https://truecoach.co/">Link</a></td>
            <td>Collaboration between coaches and clients</td>
            <td>Personal trainers</td>
            <td>Comments</td>
        </tr>
        <tr>
            <td>My Pt HUB</td>
            <td><a href="https://www.mypthub.net/">Link</a></td>
            <td>Video library</td>
            <dtd>Audience</dtd>
            <td>Comments</td>
        </tr>
          <tr>
            <td>Coaches eye</td>
            <td><a href="https://www.coachseye.com/">Link</a></td>
            <td>Video analysis</td>
            <td>Audience</td>
            <td>Comments</td>
        </tr>
          <tr>
            <td>Polar beat</td>
            <td><a href="https://www.coachseye.com/">Link</a></td>
            <td>Ties in with Polar eco system</td>
            <td>Audience</td>
            <td>Comments</td>
        </tr>
          <tr>
            <td>Mindful break</td>
            <td><a href="https://chrome.google.com/webstore/detail/mindful-break/onjcfgnjjbnflacfbnjaapcbiecckilk?hl=en-GB">Link</a></td>
            <td>Integrated to chrome</td>
            <td>Audience</td>
            <td>Comments</td>
        </tr>
        </tbody>
      </table>
    </div>
  </Layout>
</template>

<script>
export default {}
</script>

<style scoped>
.competitor-header {
  padding: 2rem 0 4rem 0;
}
.competitor-title {
  font-size: 4rem;
  margin: 0 0 4rem 0;
  padding: 0;
}
.sender-info {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}
.sender-info > div {
  flex: 1;
  margin-right: 4rem;
}
.sender-info > div:last-of-type {
  margin: 0;
}
input:focus,textarea:focus {
  border-color: var(--color-contrast-1);
}
input,textarea {
  background: transparent;
  border: 1px solid var(--color-base-1);
  outline: none;
  border-radius: 0.3rem;
  padding: 0.8rem 1rem;
  color: inherit;
  font-size: 1rem;
  width: 100%;
}
textarea {
  resize: none;
  height: 140px;
}
.button {
  color: var(--color-base);
  background: var(--color-contrast);
  outline: none;
  border: 0;
  font-size: 0.8rem;
  padding: 0.8rem 1.6rem;
  border-radius: 0.3rem;
  margin-top: 2rem;
  cursor: pointer;
  transition: opacity 0.25s ease;
  font-size: 500;
  letter-spacing: 0.035em;
}
.button:hover {
  opacity: 0.6;
}
.button:focus {
  border: 1px solid var(--color-base-1);
}
</style>


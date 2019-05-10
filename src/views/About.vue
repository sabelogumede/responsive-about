<template>
  <div class="about-card">
    <div class="card-title">
      <img height="50px" src="https://i.pinimg.com/originals/d3/69/d9/d369d9056795f553e244da66e8297cca.png" alt="avatar" class="avatar">
      <div class="title-text-content">
        <p>About me</p>
        <h2>Sabelo Gumede</h2>
      </div>
    </div>
    <div class="card-content">
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Molestiae laboriosam quibusdam sit dignissimos suscipit asperiores quaerat, 
        neque, distinctio, vitae eos consequatur modi dolorum? Debitis quaerat 
        dolorem numquam! Nemo, asperiores ratione.
      </p>
      <table width="100%">
        <tr>
          <th>Requirement</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>PhotoShop, Figma, Canva, Adobe XD</td>
        </tr>
        <tr>
          <td>Back-end</td>
          <td>Node.js, Expresss.js, Mongo, GraphQL</td>
        </tr>
        <tr>
          <td>ML</td>
          <td>MLS, Tensorflow, Algorithm Design</td>
        </tr>
        <tr>
          <td>Shp</td>
          <td>Scripe, Payment, E-commerce, CMS</td>
        </tr>
      </table>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Molestiae laboriosam quibusdam sit dignissimos suscipit asperiores quaerat, 
        neque, distinctio, vitae eos consequatur modi dolorum? Debitis quaerat 
        dolorem numquam! Nemo, asperiores ratione.
      </p>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Molestiae laboriosam quibusdam sit dignissimos suscipit asperiores quaerat, 
        neque, distinctio, vitae eos consequatur modi dolorum? Debitis quaerat 
        dolorem numquam! Nemo, asperiores ratione.
      </p>
    </div>
  </div>
</template>

<style lang="sass" scoped>
.about-card
  background: #333
  padding: 3em
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center 
    background: #222
    border-radius: 10px
    .avatar
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
    .title-text-content
      p
        margin-bottom: 0
        color: rgb(210, 210, 210)
      h2
        margin-top: 0

  .card-content p 
    line-height: 1.5
    margin: 30px auto 
  table
    border-spacing: 0px
    margin: 50px auto
    tr th, tr td
      border: 1px solid white
      border-top: none
      padding: 10px
      text-align: center
      &:first-of-type
        border-left: none
      &:nth-of-type(2)
        border-right: none

</style>

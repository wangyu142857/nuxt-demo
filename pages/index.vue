<template>
  <!-- <Tutorial/> -->
  <b-container fluid>
    <b-row>
      <b-col cols="12">
        <div class="header">header</div>
      </b-col>
    </b-row>
    <b-row>
      <b-col class="aside" cols="3">aside</b-col>
      <b-col class="main">
          <b-row>
            <b-col cols="3">
              <div class="item-container"></div>
            </b-col>
            <b-col cols="3" class="row1-col2">
              <div class="item-container"></div>
            </b-col>
            <b-col cols="6">
              <div class="item-container"></div>
            </b-col>
          </b-row>
          <b-row>
            <b-col cols="6" class="row2-col1">
              <div class="item-container"></div>
            </b-col>
            <b-col cols="6">
              <div class="item-container"></div>
            </b-col>
          </b-row>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
.header {
  height: 50px;
  line-height: 50px;
  background: #eeeeee;
  margin: 0 -15px;
}
.aside {
  background: #dddddd;
  flex: 0 0 280px;
}
.main {
  height: calc(100vh - 50px);
  padding: 5px 20px;
}
.main > .row {
  height: 50%;
  padding-top: 5px;
  padding-bottom: 5px;
}
.main > .row > div {
  height: 100%;
  padding: 0 5px;
}

.item-container {
  background: #cccccc;
  height: 100%;
}
</style>
<script setup></script>

<template>
  <div class="box" id="skills">
    <div class="row">
      <div>
        <div style="margin: 10px 0 10px 0; font-size: 40px">Microsoft skills</div>
        <div style="display: flex; justify-content: center">
          <div style="align-items: center;">
              <div class="row" style="align-items: center gap: 20px ">
                <img style="margin: 0 0 10px 0;"
                  src="../assets/logo skills/Word.png"
                  alt=""
                />
                <div style="margin: 5px 0 0 0;">Microsoft word</div>
            </div>
            <div class="row" style="align-items: center gap: 20px">
              <img style="margin: 0 0 10px 0;"
                src="../assets/logo skills/Powerpoint.png"
                alt=""
              />
              <div style="margin: 5px 0 0 0;" >Microsoft Powerpoint</div>
            </div>
            <div class="row" style="align-items: center gap: 20px">
              <img style="margin: 0 0 10px 0;"
                src="../assets/logo skills/Excel.png"
                alt=""
              />
              <div style="margin: 5px 0 0 0;">Microsoft Excel</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div style="margin: 30px 0 0 0;">
        <img src="../assets/logo skills/mic.png" alt="" width="150px">
    </div>
  </div>
</template>

<style scoped>
.box {
  position: relative; /*กางอาณาเขต*/
  display: flex;
  justify-content: center;
  margin: 0 0 0 50px;
  gap: 20px;
}
.row img {
  width: 30px;
}
.row {
  display: flex;
  gap: 20px;
}
.space {
  margin: 10px 0 10px 0;
}
</style>

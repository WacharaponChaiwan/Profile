<script setup></script>

<template>
  <div class="box" id="about">
    <div>
      <div style="margin: 0 0 20px 0; font-size: 40px">About Me</div>
      <div class="row">
        <div>
          <div>Educational</div>
          <div class="row" style="padding: 10px 0 0 0; align-items: center">
            <img src="../assets/logoschool/Boonpng.png" alt="" />
            <div>ใบบุญลำพูน</div>
          </div>
          <div class="row" style="align-items: center">
            <img src="../assets/logoschool/PTl.png" alt="" />
            <div>ประตูลี้ ลำพูน</div>
          </div>
          <div class="row" style="align-items: center">
            <img src="../assets/logoschool/output.png" alt="" />
            <div>ส่วนบุญโญฯ</div>
          </div>
          <div class="row" style="align-items: center">
            <img src="../assets/logoschool/MJU_LOGO.svg.png" alt="" />
            <div>เเม่โจ้</div>
          </div>
        </div>
        <div class="line"></div>
        <div>
          <div>Personal Information</div>
          <div>
            <img src="" alt="" />
            <div>Nickname : Teung(เติ้ง)</div>
          </div>
          <div>
            <img src="" alt="" />
            <div>Brith : 19-02-2002</div>
          </div>
          <div>
            <img src="" alt="" />
            <div>Age : 20</div>
          </div>
          <div>
            <img src="" alt="" />
            <div>Nationality : Thai</div>
          </div>
          <div>
            <img src="" alt="" />
            <div>Mobile : +6661-272-1096</div>
          </div>
          <div>
            <img src="" alt="" />
            <div>Email : teung018@gmail.com</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.box {
  position: relative; /*กางอาณาเขต*/
  display: flex;
  justify-content: center;
  text-align: center;
  margin: 50px 0 50px 0;
}
.row {
  display: flex;
  gap: 30px;
}
.line {
  height: 240px;
  width: 5px;
  border-radius: 10px;
  background-color: black;
}
.row img {
  width: 40px;
}
</style>

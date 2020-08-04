<template>
  <section class="journey-way">
    <div class="way-title">
      <h2>way to travel with <span>us</span></h2>
      <p>
        Thông báo của bộ Ngoại Giao Mỹ cho biết trong cuộc gặp gỡ này, ngoại
        trưởng Mỹ Mike Pompeo và đồng nhiệm Indonesia Retno Marsudi đã thảo luận
        về mối quan hệ phòng thủ song phương và tình hình khủng hoảng trong khu
        vực do tham vọng của Trung Quốc muốn làm chủ gần như toàn bộ biển Đông
        gây ra.
      </p>
    </div>
    <div class="way-move">
      <div class="sourneyicon">
        <img src="../../assets/images/Icon1.svg" alt="" />
        <h3>TRAVEL WITH BUS</h3>
        <p>
          Vui là vì các địa danh Bourgogne và Champagne gần đây đã được UNESCO
          công nhận là di sản văn hóa thế giới. Buồn là vì thời tiết năm nay
          không mấy thuận lợi, thêm vào đó là sự cạnh tranh khá dữ dội của các
          hiệu rượu nho nước ngoài, điển hình nhất là rượu Prosecco, một loại
          vang trắng có sủi bọt của Ý.
        </p>
      </div>
      <div class="sourneyicon">
        <img src="../../assets/images/Icon2.svg" alt="" />
        <h3>TRAVEL WITH AIRPLANE</h3>
        <p>
          Vui là vì các địa danh Bourgogne và Champagne gần đây đã được UNESCO
          công nhận là di sản văn hóa thế giới. Buồn là vì thời tiết năm nay
          không mấy thuận lợi, thêm vào đó là sự cạnh tranh khá dữ dội của các
          hiệu rượu nho nước ngoài, điển hình nhất là rượu Prosecco, một loại
          vang trắng có sủi bọt của Ý.
        </p>
      </div>
      <div class="sourneyicon">
        <img src="../../assets/images/Icon3.svg" alt="" />
        <h3>TRAVEL WITH CAR</h3>
        <p>
          Vui là vì các địa danh Bourgogne và Champagne gần đây đã được UNESCO
          công nhận là di sản văn hóa thế giới. Buồn là vì thời tiết năm nay
          không mấy thuận lợi, thêm vào đó là sự cạnh tranh khá dữ dội của các
          hiệu rượu nho nước ngoài, điển hình nhất là rượu Prosecco, một loại
          vang trắng có sủi bọt của Ý.
        </p>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.journey-way {
  // display: inline;
  // align-items: center;
  // justify-content: center;
  .way-title {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    width: 100%;
    min-width: 100%;
    padding: 20px 10px 20px;
    h2 {
      text-transform: uppercase;
    }
    span {
      color: #037942;
    }
    p {
      font-size: 16px;
      font-weight: 700;
    }
  }
  .way-move {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    .sourneyicon {
      justify-content: center;
      align-items: center;
      display: flex;
      flex-direction: column;
      padding: 20px;
    }
  }
}
</style>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'JourneyWay',
})
</script>

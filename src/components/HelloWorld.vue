<template>
  <div>
    <!-- Top -->
    <div class="row">
      <div class="col-2">
        <div class="wrapper-left flex">
          <button class="btn btn-outline-danger is-button-book">Danh sách đã mượn</button>
        </div>
      </div>
      <div class="col-10">
        <div class="wrap-right-top">
          <h4 class="wrap-right-top__title">Danh sách book có trong thư viện</h4>
          <div class="wrap-controller-top flex-row">
            <div class="flex-row wrap-right-bottom">
              <button class="is-button-top btn btn-secondary mr-1 -is-active">Tất cả</button>
              <button class="is-button-top btn btn-secondary mr-1">Mới thêm vào thư viện</button>
              <button class="is-button-top btn btn-secondary mr-1">Đọc nhiều nhất</button>
              <button class="is-button-top btn btn-secondary">Sách hiếm</button>
            </div>
            <div class="flex-row wrap-search">
              <input type="text" class="wrap-search__input form-control" placeholder="Nhập từ khóa tìm kiếm">
              <button type="submit" class="wrap-search__button">
                <i class="fas fa-search"></i>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Content -->
    <div class="row">
      <div class="col-2">
        <div class="wrapper-left flex">
          <div class="wrap-row">
            <i class="fas fa-book wrap-row__icon"></i>
            <span class="wrap-row__text">Mới xem gần đây</span>
          </div>
          <div class="wrap-row">
            <i class="fas fa-globe-asia wrap-row__icon"></i>
            <span class="wrap-row__text">Danh sách book</span>
          </div>
          <div class="wrap-row">
            <i class="fas fa-shopping-cart wrap-row__icon"></i>
            <span class="wrap-row__text">Buy books</span>
          </div>
          <div class="wrap-row">
            <i class="fas fa-star wrap-row__icon"></i>
            <span class="wrap-row__text">Sách ưu chuộng</span>
          </div>
          <div class="wrap-row">
            <i class="fas fa-history wrap-row__icon"></i>
            <span class="wrap-row__text">Lịch sử đã mượn</span>
          </div>
          <hr class="is-split">
          <div class="wrap-mark">
            <i class="fas fa-circle wrap-mark__icon -red"></i>
            <span class="wrap-mark__text">Sách chuyên ngành</span>
          </div>
          <div class="wrap-mark">
            <i class="fas fa-circle wrap-mark__icon -yellow"></i>
            <span class="wrap-mark__text">Truyện ngôn tình</span>
          </div>
          <div class="wrap-mark">
            <i class="fas fa-circle wrap-mark__icon -green"></i>
            <span class="wrap-mark__text">Sách học ngôn ngữ</span>
          </div>
          <div class="wrap-mark">
            <i class="fas fa-circle wrap-mark__icon -purple"></i>
            <span class="wrap-mark__text">Sách học thuật</span>
          </div>
          <hr class="is-split">
          <div class="wrap-note">
            <i class="far fa-clock wrap-note__icon"></i>
            <span class="wrap-note__text">Sau khi đặt sách xong, bạn hãy mang thẻ sinh viên xuống thư viện</span>
          </div>
          <div class="wrap-note">
            <i class="far fa-clock wrap-note__icon"></i>
            <span class="wrap-note__text">Thư viện sẽ cho mượn sách trong khoảng từ 8h30 đến 21h30 từ thứ 2 đến thứ 6 hàng tuầng</span>
          </div>
        </div>
      </div>
      <div class="col-10">
        <div class="row pr-2">
          <div class="col one-book">
            <img src="../images/book-cover.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover2.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover3.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover4.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover5.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col one-book">
            <img src="../images/book-cover6.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover7.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover8.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover9.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <div class="col one-book">
            <img src="../images/book-cover10.png" alt="book">
            <h5 class="one-book__title">Jewels of Nizam</h5>
            <p class="one-book__author">by Goota Devi</p>
            <div class="one-book__start flex-row">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.wrap-right-top__title {
  color: #444c63;
}

.is-button-top {
  font-weight: 100;
  height: 30px;
  font-size: 11px;
  border-radius: 20px;
}
.is-button-top.-is-active {
  background-color: #272727;
}

.wrap-controller-top {
  padding: 30px 30px 30px 0px;
  display: flex;
  justify-content: space-between;
}

.wrap-search__input {
  display: -webkit-inline-box;
  border-radius: 20px;
  height: 30px;
  font-size: 11px;
  width: 350px;
}
.wrap-search__button {
  margin-left: -35px;
  border: 0;
  background: none;
  font-size: 15px;
  color: #65676d;
}

hr.is-split {
  background-color: #19202e;
  height: 2px;
}

.wrap-row {
  padding-left: 20px;
  color: #78829d;
  font-size: 14px;
  padding-bottom: 10px;
}
.wrap-row__icon {
  margin-right: 10px;
}
.wrap-row__text {
  font-size: 12px;
  font-weight: 100px;
}

.wrap-mark {
  padding-left: 20px;
  color: #78829d;
  font-size: 12px;
  padding-bottom: 10px;
}
.wrap-mark__icon {
  margin-right: 10px;
  font-size: 8px;
}
.wrap-mark__icon.-red {
  color: red;
}
.wrap-mark__icon.-yellow {
  color: orange;
}
.wrap-mark__icon.-purple {
  color: purple;
}
.wrap-mark__icon.-green {
  color: green;
}

.wrap-note {
  padding-left: 20px;
  color: #78829d;
  font-size: 12px;
  padding-bottom: 10px;
}
.wrap-note__icon {
  margin-right: 10px;
}

.one-book {
  color: #78829d;
}
.one-book__title {
  font-size: 14px;
  color: #444c63;
  letter-spacing: 1px;
  margin-top: 10px;
  margin-bottom: 2px;
}
.one-book__author {
  font-size: 11px;
  margin-bottom: 2px;
}
.one-book__start {
  color: #ffab00;
  margin-bottom: 25buttonpx;
  font-size: 12px;
}

.is-button-book {
  border-radius: 20px;
  margin-top: 60px;
  margin-left: 17px;
}
</style>

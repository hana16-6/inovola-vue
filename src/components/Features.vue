<template>
  <div className="your-apps mb-5">
    <div className="container ">
      <div className="row mb-5 pt-5">
        <div className="col-6">
          <h3>كل ماتحتاجه لنمو متجرك فى مكان واحد</h3>
          <p>
            مميزات سوق تطبيقات زد تساعدك فى سهولة وسرعة لاستفادة من خدمات وحلول
            سوق التطبيقات لنمو متجرك ومضاعفة أرباحك
          </p>
          <ul>
            <li className="d-flex align-items-center mt-4">
              <div className="icon">
                <img src="../assets/icons/features/mail.svg" alt="" />
              </div>
              <p>سهولة إدارة وتفعيل تطبيقاتك من نفس لوحة تحكم متجرك</p>
            </li>
            <li className="d-flex align-items-center my-4">
              <div className="icon">
                <img src="../assets/icons/features/chat.svg" alt="" />
              </div>
              <p>دعم فني وتقني متكامل متوفر على مدار الساعة</p>
            </li>
            <li className="d-flex align-items-center">
              <div className="icon">
                <img src="../assets/icons/features/hand.svg" alt="" />
              </div>
              <p>أسعار تنافسية مع تجربة مجالية وباقات اشتراك متنوعة</p>
            </li>
          </ul>
        </div>
        <div className="zid_app col-6">
          <img className="w-100" src="../assets/images/zidapp.png" alt="" />
          <img
            className="Dot_pattern"
            src="../assets/images/Dot-Pattern.png"
            alt=""
          />
          <img
            className="yellow_ellipse"
            src="../assets/images/yellow-ellipse.png"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features",
};
</script>
<style scoped lang="scss">
$primary-color: #8d5da7;

.your-apps {
  background-color: #fafafced;
  h3 {
    color: $primary-color;
  }
  ul {
    list-style: none;
    li {
      .icon {
        width: 3.125rem;
        height: 3.125rem;
        box-shadow: 0.1875rem 0.125rem 0.5625rem 0 #bfbfbf;
        margin-left: 1.25rem;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;
      }
    }
  }
  .zid_app {
    position: relative;
    z-index: 10;
    .Dot_pattern {
      position: absolute;
      top: -14px;
      left: -34px;
      z-index: -1;
    }
    .yellow_ellipse {
      position: absolute;
      bottom: -45px;
      right: -30px;
      z-index: -1;
      width: 300px;
    }
  }
}
</style>
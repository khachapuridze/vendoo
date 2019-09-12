<template>
   <div class="profile-section">
       <div>
           <h6 class="profile-section__title">პირადი ინფორმაცია</h6>
       </div>
      <div class="profile-section__inputs">
           <input type="text" name="name" id="" placeholder="სახელი">
       <input class="lastname" type="text" name="surname" id="" placeholder="გვარი">
       <input type="number" class="input-id" name="id" id="" placeholder="პირადი ნომერი">
       <select class="option-input"  aria-placeholder="სქესი">
            <option value="" disabled selected hidden>სქესი</option>
            <option value="male">მდედრობითი</option>
            <option value="female">მამრობითი</option>
            <option value="other">სხვა</option>
        </select>
       <input class="option-input birth" data-placeholder="დაბადების თრიღი " type="date" name="name" id="" >
       <input type="number" name="mobile" id="" placeholder="ტელეფონის ნომერი">
       <input class="input-email" type="email" name="email" id="" placeholder="ელ.ფოსტა">

      </div>
      <p class="password-text">პაროლი</p>
      <button class="btn-change">
          <a href="/">პაროლის შეცვლა</a>
      </button>

      <p class="get-news">სიახლეების გამოწერა</p>

      <div class="wrapper">
          <div class="toggle-btn">
              <input type="checkbox" id="chk">
                <label for="chk">
                    <span></span>
                </label>
           </div>
           <p class="on-off" for="">გამორთულია</p>
        </div>
   </div>
</template>

<script>
export default {

    name: 'mainProfile',
}
</script>
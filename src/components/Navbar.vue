<template>
  <div>
    <section class="flex justify-between navbar items-center">
      <div class="flex content__navbar">
        <img
          src="./../assets/icon-navbar.png"
          alt="Logo com icone de formato de corção dentro de um triângulo."
        />
        <div class="ml-8 flex flex-col">
          <p>Animarta</p>
          <p>Today-Tomorrow</p>
        </div>
      </div>

      <div class="mt-5">
        <ul class="flex navbar__links">
          <li>Home</li>
          <li>Works</li>
          <li>About us</li>
          <li>Contact</li>
          <li class="mr-4 navbar__icon">
            <img
              src="./../assets/icon-navbar-darkmode.png"
              alt="icone do modo noturno"
              width="20"
              height="20"
              class="ml-7"
            />
          </li>
        </ul>
      </div>
    </section>
  </div>
</template>

<style scoped>
.navbar {
  margin: 20px 50px;
}
.content__navbar img {
  width: 23px;
  height: 40px;
}
.content__navbar p:nth-child(1) {
  font-family: "Viga";
  font-size: 17px;
  color: #fff;
}
.content__navbar p:nth-child(2) {
  font-family: "Viga";
  font-size: 12px;
  color: #fff;
  opacity: 50%;
}

.navbar__links {
  margin-right: 0.7vw;
}
.navbar__links li {
  margin-left: 5vw;
  font-family: "Inter";
  font-weight: bold;
  font-size: 13px;
  color: #fff;
  text-transform: uppercase;
}
.navbar__icon {
  position: relative;
  left: 40px;
}
</style>

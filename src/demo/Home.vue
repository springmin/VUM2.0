<template>
  <div>
    <page-header>
      <header-link>About</header-link>
      <header-title>VUM2.0</header-title>
    </page-header>
    <Contented>
      <header class='demos-header'>
        <h1 class="demos-title">CSS</h1>
      </header>
      <div class="grids grids-small">
        <router-link :to="{ path: '/page'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/page.png" alt="">
            </div>
            <p class="grid_label">
              Page
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'buttons'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/button.png" alt="">
            </div>
            <p class="grid_label">
              Button
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'column'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/column.png" alt="">
            </div>
            <p class="grid_label">
              Column
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'grid'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/grid.png" alt="">
            </div>
            <p class="grid_label">
              Grid
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'list'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/list.png" alt="">
            </div>
            <p class="grid_label">
              List
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'contacts'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/contacts.png" alt="">
            </div>
            <p class="grid_label">
              Contacts
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'form'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/form.png" alt="">
            </div>
            <p class="grid_label">
              Form
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'icons'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/toast.png" alt="">
            </div>
            <p class="grid_label">
              Icons
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'result'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/result.png" alt="">
            </div>
            <p class="grid_label">
              Result
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'stars'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/star.png" alt="">
            </div>
            <p class="grid_label">
              Stars
            </p>
          </a>
        </router-link>
      </div>
  
      <h2 class="demos-title">Components</h2>
      <div class="grids grids-small">
        <router-link :to="{ path: 'modal'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/modal.png" alt="">
            </div>
            <p class="grid_label">
              Modal
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'preloader'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/preloader.png" alt="">
            </div>
            <p class="grid_label">
              Preloader
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'toast'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/toast.png" alt="">
            </div>
            <p class="grid_label">
              Toast
            </p>
          </a>
        </router-link>
        <!--<router-link :to="{ path: 'tab'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/tab.png" alt="">
            </div>
            <p class="grid_label">
              Tab
            </p>
          </a>
        </router-link>-->
        <router-link :to="{ path: 'scroll'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/scroll.png" alt="">
            </div>
            <p class="grid_label">
              Scroll
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'popup'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/window.png" alt="">
            </div>
            <p class="grid_label">
              Popup
            </p>
          </a>
        </router-link>
        <router-link :to="{ path: 'popwindow'}">
          <a class="grid">
            <div class="grid_icon">
              <img src="../assets/images/home/window.png" alt="">
            </div>
            <p class="grid_label">
              PopWindow
            </p>
          </a>
        </router-link>
        <!--<a v-link="{ path: 'actions' }" class="grid">
          <div class="grid_icon">
            <img src="../assets/images/home/menu.png" alt="">
          </div>
          <p class="grid_label">
            Actions
          </p>
        </a>
        <a v-link="{ path: 'searchbar' }" class="grid">
          <div class="grid_icon">
            <img src="../assets/images/home/search.png" alt="">
          </div>
          <p class="grid_label">
            Searchbar
          </p>
        </a>
        <a v-link="{ path: 'calendar' }" class="grid">
          <div class="grid_icon">
            <img src="../assets/images/home/calendar.png" alt="">
          </div>
          <p class="grid_label">
            Calendar
          </p>
        </a>
        <a v-link="{ path: 'slide' }" class="grid">
          <div class="grid_icon">
            <img src="../assets/images/home/slide.png" alt="">
          </div>
          <p class="grid_label">
            Slide
          </p>
        </a>
        <a v-link="{ path: 'side-panel' }" class="grid">
          <div class="grid_icon">
            <img src="../assets/images/home/side.png" alt="">
          </div>
          <p class="grid_label">
            SidePanel
          </p>
        </a>
        <a v-link="{ path: 'menu' }" class="grid">
          <div class="grid_icon">
            <img src="../assets/images/home/menu.png" alt="">
          </div>
          <p class="grid_label">
            Menu
          </p>
        </a>
        <a v-link="{ path: 'circle' }" class="grid">
          <div class="grid_icon">
            <img src="../assets/images/home/circle.png" alt="">
          </div>
          <p class="grid_label">
            Circle
          </p>
        </a>-->
      </div>
    </Contented>
  </div>
</template>
<script>
import Grid from '../components/grid'
import { Header, HeaderLink, HeaderTitle } from '../components/header'
import Contented from '../components/content'

export default {
  components: {
    'page-header': Header,
    HeaderLink,
    HeaderTitle,
    Contented,
    Grid
  }
}
</script>

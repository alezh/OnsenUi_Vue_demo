<<template>
<v-ons-toolbar class="toolbar toolbar--material">
  <div class="toolbar__left toolbar--material__left">
    <span class="toolbar-button toolbar-button--material">
      <i class="zmdi zmdi-menu"></i>
    </span>
  </div>
  <div class="toolbar__center toolbar--material__center">
    {{Bar}}
  </div>
  <div class="toolbar__right toolbar--material__right">
    <span class="toolbar-button toolbar-button--material">
      <i class="zmdi zmdi-search"></i>
    </span>
    <span class="toolbar-button toolbar-button--material">
      <i class="zmdi zmdi-favorite"></i>
    </span>
    <span class="toolbar-button toolbar-button--material">
      <i class="zmdi zmdi-more-vert"></i>
    </span>
  </div>
</v-ons-toolbar>
</template>
<script>
export default {
  name:'toolbar',
  data () {
      return {
      Bar: 'Navigation Bar'
    }
  }
}
</script>

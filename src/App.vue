<script>
import logo from './assets/logo.png'
export default {
  name: 'App',
  render () {
    return (
      <div id="app">
        <img src={logo} />
        <router-view />
      </div>
    )
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
    <footer class="footer has-cards">
            <hr>
            <div class="row align-items-center justify-content-md-between" style="text-align:center">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        Maró Hajnalka | maro.hajnalka@gmail.com
                    </div>
                </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>

<template>
  <div class="footer">
    <div class="links">
      <a href="https://ant.design/" target="_blank">Ant Design</a>
      <a href="https://vue.ant.design/" target="_blank">Vue Antd</a>
      <a
        href="https://github.com/wongqingbin/ant-design-vue-pro"
        target="_blank"
      >
        <a-icon type="github" />
      </a>
      <a
        href="https://wongqingbin.github.io/"
        target="_blank"
      >博客</a>
    </div>
    <div class="copyright">
      Copyright
      <a-icon type="copyright" /> 2020 <span>Wang QingBin</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GlobalFooter',
  data () {
    return {}
  }
}
</script>

<style lang="less" scoped>
.footer {
  padding: 0 16px;
  margin: 48px 0 24px;
  text-align: center;

  .links {
    margin-bottom: 8px;

    a {
      color: rgba(0, 0, 0, 0.45);

      &:hover {
        color: rgba(0, 0, 0, 0.65);
      }

      &:not(:last-child) {
        margin-right: 40px;
      }
    }
  }
  .copyright {
    color: rgba(0, 0, 0, 0.45);
    font-size: 14px;
  }
}
</style>

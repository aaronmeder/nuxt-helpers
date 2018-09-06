<script>
export default {
  head() {
    return {
      bodyAttrs: {
        class: `page-${this.$route.params.page}`,
      },
    };
  },
};
</script>

<template>
  <div>aaaaa</div>
</template>

<script>
export default {
  name: 'top'
}
</script>

<style lang="stylus">
.comment-children
  .comment-children
    margin-left 1.5em

.comment
  border-top 1px solid #eee
  position relative
  .by, .text, .toggle
    font-size .9em
    margin 1em 0
  .by
    color #828282
    a
      color #828282
      text-decoration underline
  .text
    overflow-wrap break-word
    a:hover
      color #ff6600
    pre
      white-space pre-wrap
  .toggle
    background-color #fffbf2
    padding .3em .5em
    border-radius 4px
    a
      color #828282
      cursor pointer
    &.open
      padding 0
      background-color transparent
      margin-bottom -0.5em
</style>

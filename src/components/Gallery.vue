<template>
    <div class="gallery">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img class="star" src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
      <img src="https://img.purch.com/h/1400/aHR0cDovL3d3dy5zcGFjZS5jb20vaW1hZ2VzL2kvMDAwLzA3NC84NDQvb3JpZ2luYWwvaGlzcGFzYXQuanBn">
    </div>
</template>

<script>
import { timeAgo } from '../util/filters'

export default {
  name: 'news-item',

}
</script>

<style lang="stylus">
.gallery
  background-color #fff
  padding 5px 5px 5px 5px
  border-bottom 1px solid #eee
  position relative
  line-height 20px
  img
    width 20rem
    height 20rem
    margin 2rem
  .star
    width 44rem
    height 44rem
    margin 2rem
  .score
    color #ff6600
    font-size 1.1em
    font-weight 700
    position absolute
    top 50%
    left 0
    width 80px
    text-align center
    margin-top -10px
  .meta, .host
    font-size .85em
    color #828282
    a
      color #828282
      text-decoration underline
      &:hover
        color #ff6600
</style>

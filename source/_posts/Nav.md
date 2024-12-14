---
title: 导航
---
<style>
  div > a {
    display: flex;
    flex-direction: column;
    align-items: center; /* 水平居中对齐 */
    text-decoration: none;
    color: inherit;
  }
  div > a > h1 {
    margin: 5px; /* 移除h1标签的默认外边距 */
    font-size: 2em;
  }

  /* 默认情况下，为桌面视图设置样式 */
  .link-container {
    display: flex;
    justify-content: space-around;
    padding: 5px;
  }

  .link-container + .link-container {
    padding-top: 20px;
  }

  @media only screen and (max-width: 768px) {
    /* 当屏幕宽度小于或等于768px时，应用以下样式 */
    .link-container {
      flex-direction: column;
      align-items: center;
      padding: 10px;
    }

    .link-container a {
      margin: 10px 0; /* 在每个链接之间添加上下间距 */
    }
  }
</style>

<div class="link-container">
  <a href="https://stzr.cjhcjh6.top" target="_blank">
    <h1>什亭之人的小站</h1>
    <img src="/imgs/1.png" alt="什亭之人" width="300" height="180"/>
  </a>
  <a href="https://cuyu.cjhcjh6.top" target="_blank">
    <h1>簇雨cuyu的博客</h1>
    <img src="/imgs/2.png" alt="图片描述2" width="300" height="180"/>
  </a>
  <a href="https://schale.us.kg" target="_blank">
    <h1>星影の博客</h1>
    <img src="/imgs/3.png" alt="图片描述3" width="300" height="180"/>
  </a>
</div>
<div class="link-container">
  <a href="https://modpack.rduteam.top/" target="_blank">
    <h1>什亭之人的整合包发布</h1>
    <img src="/imgs/4.png" alt="图片描述1" width="300" height="180"/>
  </a>
  <a href="https://mcweb.rduteam.top/" target="_blank">
    <h1>mc余梦再现服务器</h1>
    <img src="/imgs/5.png" alt="图片描述2" width="300" height="180"/>
  </a>
  <a href="https://docs.rduteam.top/" target="_blank">
    <h1>RDUDocs文档系统</h1>
    <img src="/imgs/6.png" alt="图片描述3" width="300" height="180"/>
  </a>
</div>
<template>
    <div id="app">
        <div class="wrapper">
            <com-header></com-header>
            <router-view></router-view>
            <com-footer></com-footer>
        </div>
    </div>
</template>

<style lang="scss">
    @import '~@assets/styles/base.scss';
    @import '~@assets/styles/reset.scss';
    @import '~@assets/styles/common.scss';
    html,
    body {
        height: 100%;
    }
    * {
        margin: 0;
        padding: 0;
    }
    #app {
        height: 100%;
    }
    
    body {
        font-family: 'Helvetica Neue', Helvetica, 'PingFang SC', 'Hiragino Sans GB', 'Microsoft YaHei', SimSun, sans-serif;
        overflow: auto;
        font-weight: 400;
        -webkit-font-smoothing: antialiased;
    }
    
    a {
        color: #4078c0;
        text-decoration: none;
    }
    
    button,
    input,
    select,
    textarea {
        font-family: inherit;
        font-size: inherit;
        line-height: inherit;
        color: inherit;
    }
    
    .hljs {
        line-height: 1.8;
        font-family: Menlo, Monaco, Consolas, Courier, monospace;
        font-size: 12px;
        padding: 18px 24px;
        background-color: #f9fafc;
        border: solid 1px #eaeefb;
        margin-bottom: 25px;
        border-radius: 4px;
        -webkit-font-smoothing: auto;
    }
</style>

<script>
    export default {};
</script>

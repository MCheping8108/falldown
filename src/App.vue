<script>
export default {
    data() {
        return {
            currentComponent: null,
        }
    },
    methods: {
        showWiki() {
            this.currentComponent = 'Wiki';
        }
    }
}
</script>

<template>
    <li></li>
    <li></li>
    <div id="logo">
        <img src="./assets/images/logo-4.png" width="300px" height="300px">
    </div>
    <li></li>
    <li></li>
    <div class="text-1">
        <video width="auto" height="720px" controlslist="nodownload" controls>
            <source src="./assets/videos/FallDown.mp4" type="video/mp4">
        </video>
    </div>
    <li></li>
    <li></li>
    <div class="bottom">
        <br>
        <br>
        <h1>游戏介绍</h1>
        <p>Wilson，听从了一个陌生“人”的劝告，为了拯救他被夺走生命的母亲。<br>
            他来到了树林，走上了旋转楼梯，踏上了拯救母亲的旅途，<br>
            可是他发现他来到的不是他想象的那般顺利。<br>
            因为他来到的不是救赎了路程，而是地狱般的折磨......</p>

        <div class="bottom-1">
            <br>
            <h1>本游戏由三个团队支持</h1>

            <a href="https://space.bilibili.com/1804596940" target="_blank" class="team cubeTeam"><img
                    src="./assets/images/cubeLogoTeam.jpg" width="300px" height="300px" title="正方体制作团队"></a>



            <a href="https://space.bilibili.com/701274997" target="_blank" class="team fortynineTeam"
                onclick="alert('旧的团队官方号因不可抗因素被永久关闭，我们推荐您去看看新的官方号\nhttps://space.bilibili.com/1962679368')"><img
                    src="./assets/images/49-team.jpg" width="300px" height="300px" title="吾乃肆玖创作团队"></a>



            <a href="./JavaScript/help.html" target="_blank" class="team NothereTeam"><img src="./assets/images/NOTHERETeam.jpg"
                    width="300px" height="300px" title="御鬼创作团队"></a>


            <br>
            <br>
            <a href="#" @click="showWiki">
                <button class="wiki-button custom-btn" :is="currentComponent">点击这里查看说明</button>
            </a>

            <a href="https://cube.fandom.com/zh/wiki/Fall_down" target="_blank">
                <button class="wiki-button custom-btn">点击这里查看FandomWiki</button>
            </a>

            <div class="developer">
                <h1>游戏开发者：梓烨-Lan</h1>
                <a href="https://space.bilibili.com/381324503"> <img src="./assets/images/ziye-lan-nobackground.png"
                        title="梓烨-Lan"> </a>
            </div>

            <br>
            <marquee>开发者留言：游戏正在开发，敬请期待</marquee>
            <br>
            <br>
            <div class="website-developer">
                <p>网站由<a href="https://space.bilibili.com/2025948439">和平peaceful</a>和<a
                        href="https://space.bilibili.com/381324503">梓烨-Lan</a>联合搭建</p>
            </div>
            <br>
            <br>
        </div>

    </div>
</template>

<style scoped></style>

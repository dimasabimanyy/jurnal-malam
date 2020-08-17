<template>
    <div id="recent-post">
        <div class="recent-section-wrap">
            <h1>Postingan Terbaru</h1>
            <div class="recent-post-box">
                <div class="recent-post-img"><img src="~/assets/images/hero.jpg" alt=""></div>
                <div class="recent-post-wrap-child">
                    <h2 class="recent-post-title">Magical Christmas Markets Around Europe - The Year of Booming</h2>
                    <div class="recent-post-info">
                        <div class="author-image">
                            <img src="~/assets/images/primary.jpg" alt="">
                        </div>
                        <div class="recent-author">
                            <h4>Dimas Abimanyu</h4>
                            <div class="recent-post-date">
                                21 Agustus 2020
                            </div>
                        </div>
                    </div>
                    <p class="recent-post-preview">
                        Far far away from dagestan. Behind the great..
                    </p>
                </div>
            </div>

            <div class="recent-post-box">
                <div class="recent-post-img"><img src="~/assets/images/hero.jpg" alt=""></div>
                <div class="recent-post-wrap-child">
                    <h2 class="recent-post-title">Magical Christmas Markets Around Europe - The Year of Booming</h2>
                    <div class="recent-post-info">
                        <div class="author-image">
                            <img src="~/assets/images/primary.jpg" alt="">
                        </div>
                        <div class="recent-author">
                            <h4>Dimas Abimanyu</h4>
                            <div class="recent-post-date">
                                21 Agustus 2020
                            </div>
                        </div>
                    </div>
                    <p class="recent-post-preview">
                        Far far away from dagestan. Behind the great.. 
                    </p>
                </div>
            </div>

            <div class="recent-post-box">
                <div class="recent-post-img"><img src="~/assets/images/hero.jpg" alt=""></div>
                <div class="recent-post-wrap-child">
                    <h2 class="recent-post-title">Magical Christmas Markets Around Europe - The Year of Booming</h2>
                    <div class="recent-post-info">
                        <div class="author-image">
                            <img src="~/assets/images/primary.jpg" alt="">
                        </div>
                        <div class="recent-author">
                            <h4>Dimas Abimanyu</h4>
                            <div class="recent-post-date">
                                21 Agustus 2020
                            </div>
                        </div>
                    </div>
                    <p class="recent-post-preview">
                        Far far away from dagestan. Behind the great..
                    </p>
                </div>
            </div>

            <div class="recent-post-box">
                <div class="recent-post-img"><img src="~/assets/images/hero.jpg" alt=""></div>
                <div class="recent-post-wrap-child">
                    <h2 class="recent-post-title">Magical Christmas Markets Around Europe - The Year of Booming</h2>
                    <div class="recent-post-info">
                        <div class="author-image">
                            <img src="~/assets/images/primary.jpg" alt="">
                        </div>
                        <div class="recent-author">
                            <h4>Dimas Abimanyu</h4>
                            <div class="recent-post-date">
                                21 Agustus 2020
                            </div>
                        </div>
                    </div>
                    <p class="recent-post-preview">
                        Far far away from dagestan. Behind the great..
                    </p>
                </div>
            </div>

            <div class="recent-post-box">
                <div class="recent-post-img"><img src="~/assets/images/hero.jpg" alt=""></div>
                <div class="recent-post-wrap-child">
                    <h2 class="recent-post-title">Magical Christmas Markets Around Europe - The Year of Booming</h2>
                    <div class="recent-post-info">
                        <div class="author-image">
                            <img src="~/assets/images/primary.jpg" alt="">
                        </div>
                        <div class="recent-author">
                            <h4>Dimas Abimanyu</h4>
                            <div class="recent-post-date">
                                21 Agustus 2020
                            </div>
                        </div>
                    </div>
                    <p class="recent-post-preview">
                        Far far away from dagestan. Behind the great..
                    </p>
                </div>
            </div>
            <a>
                <button class="btn-show-more">Lebih Banyak</button>
            </a>
        </div>
    </div>
</template>

<style lang="scss" scoped>
#recent-post{
    // background: maroon;
    width: 65%;
    // padding: 7em 0;
    .recent-section-wrap{
        width: 100%;
        .btn-show-more{
            width: 150px;
            height: 40px;
            background: $primary-color;
            border: none;
            color: $white;
            font-weight: 500;
            font-family: $poppins;
            border-radius: 3px;
            cursor: pointer;
            margin-top: 1em;
        }
        h1{
		font-size: 35px;
		line-height: 43px;
        margin-bottom: 1.5em;
        text-align:left;
        }
        .recent-post-box{
            display: flex;
            margin-bottom: 2em;
            .recent-post-img{
                width: 35%;
                height: 200px;
                img{
                    width: 100%;
                    height: 100%;
                    object-fit: cover;
                    border-radius: 3px;
                }
            }
            .recent-post-wrap-child{
                width: 50%;
                // background: maroon;
                margin-left: 2.5em;
                .recent-post-title{
                    font-size: 20px;
                    line-height: 30px;
                    margin-bottom: .6em;
                }
                .recent-post-info{
                    display: flex;
                    margin-bottom: .8em;
                    .author-image{
                        width: 40px;
                        border-radius: 20px;
                        img{
                            width: 100%;
                            border-radius: 20px;
                        }
                    }
                    .recent-author{
                        margin-left: 1em;
                        h4{
                            font-size: 15px;
                            font-weight: 500;
                        }
                        .recent-post-date{
                            font-size: 13px;
                            line-height: 18px;
                            font-family: $poppins;
                        }
                    }
                }
                .recent-post-preview{
                    font-size: 16px;
                    line-height: 24px;
                }
            }
        }
    }
}
</style>
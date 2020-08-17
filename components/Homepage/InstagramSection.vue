<template>
    <div id="instagram-section">
        <div class="social-icon">
            <h4>Follow us : </h4>
            <div class="icons">
                <span class="icon-wrap">
                    <a href="">
                        <font-awesome-icon :icon="['fab', 'youtube']" :class="icon" style="fontSize:22px;" />
                    </a>
                </span>
                <span class="icon-wrap">
                    <a href="">
                        <font-awesome-icon :icon="['fab', 'instagram']" :class="icon" style="fontSize:22px;"/>
                    </a>
                </span>
                <span class="icon-wrap">
                    <a href="">
                        <font-awesome-icon :icon="['fab', 'github']" :class="icon" style="fontSize:22px;" />
                    </a>
                </span>
            </div>
        </div>
        <div class="gray-line"></div>
        <div class="feed-layout">
            <div class="user-info">
                <h3>dimasabimanyy_</h3>
                <a>
                    <button class="btn-follow-ig">Follow</button>
                </a>
            </div>
            <div class="feed-wrap">
                <a>
                    <div class="image-box"><img src="~/assets/images/hero.jpg"></div>
                </a>
                <a>
                    <div class="image-box"><img src="~/assets/images/hero.jpg"></div>
                </a>
                <a>
                    <div class="image-box"><img src="~/assets/images/hero.jpg"></div>
                </a>
                <a>
                    <div class="image-box"><img src="~/assets/images/hero.jpg"></div>
                </a>
                <a>
                    <div class="image-box"><img src="~/assets/images/hero.jpg"></div>
                </a>
                <a>
                    <div class="image-box"><img src="~/assets/images/hero.jpg"></div>
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    #instagram-section{
        width: 30%;
        // background: #ccc;
        .social-icon{
            margin-bottom: 2em;
            display:flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            .icons{
                .icon-wrap{
                    background: $blue-light;
                    display: inline-block;
                    padding: 10px;
                    border-radius: 50px;
                    margin-left: 10px;
                    a{
                        color: #000;
                    }
                }
            }
            h4{
                color: $gray;
                font-size: 20px;
                line-height: 30px;
            }   
        }
        .gray-line{
            width: 100%;
            height: 1px;
            background: $gray;
            opacity: .2;
            margin-bottom: 2em;
        }
        .feed-layout{
            .user-info{
                display: flex;
                justify-content: space-between;
                margin-bottom: 1.5em;
                .btn-follow-ig{
                    width: 100px;
                    height: 30px;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    background: linear-gradient(to right, #ff9f20 , #b52ab8);
                    border: none;
                    color: $white;
                    font-family: $poppins;
                    font-size: 13px;
                    font-weight: 500;
                    border-radius: 3px;
                }
            }
            .feed-wrap{
                display: grid;
                grid-template-columns: 1fr 1fr;
                grid-gap: 1.2em;
                grid-auto-flow: row;
                .image-box{
                    height: 170px;
                    img{
                        border-radius: 3px;
                        width: 100%;
                        height: 100%;
                        object-fit: cover;
                    }
                }
            }
        }
    }
</style>
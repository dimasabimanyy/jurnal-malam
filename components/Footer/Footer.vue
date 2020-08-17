<template>
    <footer>
        <div class="footer-wrapper">
            <div class="footer-info-wrap container">
                <ul>
                    <!-- <li>
                        <a href="">
                            <i class="fa fa-facebook"></i>
                        </a>
                    </li> -->
                </ul>
            </div>
            <div class="copyright">
                &copy; 2020 Dimas Abimanyu
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
footer{
    position: relative;
    width: 100%;
    background: $white;
    padding: 3em 0;
    .copyright{
        width: 100%;
        text-align: center;
        font-family: $poppins;
        color: $gray;
        font-size: 15px;
    }
}
footer:before{
    content: '';
    width: 100%;
    height: 1px;
    background: #ccc;
    position: absolute;
    top: 0;
    left: 0;
    opacity: .7;
}
</style>
<template>
    <div id="homepage-subs">
        <h3>Newsletter</h3>
        <p>
            Stay tuned with news and best advice, no spam or other unconvenient talk.
        </p>
        <form action="">
            <input type="text" placeholder="Your e-mail">
            <button class="btn-subscribe">
                Subscribe
            </button>
        </form>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
#homepage-subs{
    width: 47%;
    margin: 3em 0;
    background: transparent;
    h3{
        font-size: 22px;
        line-height: 28px;
        margin-bottom: 1em;
    }
    p{
        font-size: 16px;
        font-weight: 400;
        line-height: 26px;
        margin-bottom: 1.5em;
    }
    form{
        width: 100%;
        background: $white;
        display: grid;
        grid-template-columns: 80% 20%;
        padding: 3px;
        border-radius: 3px;
        border: 1px solid #ccc;
        input{
            font-family: $poppins;
            border: none;
            outline: none;
            padding: 10px;
            font-size: 15px;
            line-height: 20px;
        }
        button{
            background: $primary-color;
            color: $white;
            font-weight: 500;
            font-family: $poppins;
            outline: none;
            border: 1px solid $primary-color;
            border-radius: 3px;
        }
    }
}
</style>